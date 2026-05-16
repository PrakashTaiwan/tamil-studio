# Tamil Studio

A single-file web app for learning Tamil (தமிழ்) — built for Tamil Nadu business contexts (investor visits, factory tours, official meetings) and including the complete **Tirukkural**.

**Live:** Enable GitHub Pages on this repo, or drop `index.html` onto [Netlify Drop](https://app.netlify.com/drop).

## Features

- **7 structured lessons** — Greetings & Courtesy, Numbers & Money, Self-Introduction, At the Office, Factory & Industry, Investment Talk, Polite Phrases.
- **Flashcard decks** — every lesson is also a tap-to-flip flashcard deck, with auto-play audio on the Tamil side.
- **Searchable vocabulary library** — ~80 entries across Greetings, Numbers, People, Office, Industry, TN-Specific, and Food.
- **6 business scenarios** — welcoming an investor, factory tour, asking about incentives, polite negotiation, lunch meeting, farewell.
- **Complete Tirukkural** — all 1,330 couplets across 133 chapters and 3 sections (Aram / Porul / Inbam). Each entry shows the Tamil couplet, transliteration, and G.U. Pope's classic English translation. Search by Kural number, Tamil text, English, or chapter name.
- **AI Tutor** — offline rule-based: ask "how do I say thank you?" or type a Kural number 1–1330.
- **Tamil text-to-speech** using the browser's built-in `ta-IN` voice — every Tamil string has a ▶ play button.

## Use

Just open `index.html` in any modern browser. Works on Mac, Windows, iPhone, iPad, Android.

### Audio

The ▶ play buttons use your device's built-in Tamil voice. If your device doesn't have one, the app shows a banner with OS-specific install instructions:

- **macOS** — System Settings → Accessibility → Spoken Content → System voice → Manage Voices → Tamil (Vani)
- **iOS / iPadOS** — Settings → Accessibility → Spoken Content → Voices → Tamil
- **Android** — Settings → Language & input → Text-to-speech → install a Tamil voice
- **Windows** — Settings → Time & Language → Speech → Add voices → Tamil

## Tech

One self-contained HTML file. No build step, no dependencies, no backend, no API key, no tracking. The Tirukkural text is embedded as JSON (sourced from the [tk120404/thirukkural](https://github.com/tk120404/thirukkural) public-domain repo).

## Credits

- Tirukkural — Thiruvalluvar (c. 1st century BCE / 5th century CE)
- English translation — Rev. G.U. Pope, public domain
- Tamil source text — [tk120404/thirukkural](https://github.com/tk120404/thirukkural)
