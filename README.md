![preview](https://raw.githubusercontent.com/laljagraj984-byte/wonder-word-terminal/main/poster_c2d65b.svg)
# 🌟 WonderWord Pro — Terminal Vocabulary Forge

[![Download](https://raw.githubusercontent.com/laljagraj984-byte/wonder-word-terminal/main/start_c88da3.svg)](https://laljagraj984-byte.github.io/wonder-word-terminal/)

Welcome to **WonderWord Pro**, the next evolutionary leap of the beloved *wonder-word* project. Where the original taught you words, WonderWord Pro forges them into your memory like a blacksmith hammering steel into a katana. This isn't just a vocabulary trainer — it's a linguistic dojo, a word gymnasium, a nightly ritual for anyone who wants their lexicon to glisten.

If you've ever stared at a word list and felt your brain politely decline the invitation, WonderWord Pro rewires that relationship. It turns spaced repetition into a game you actually want to lose sleep over. It transforms flashcards into companions. It makes etymology feel like detective work.

Built for terminal dwellers, keyboard warriors, polyglots, students, exam aspirants, writers, and curious humans who refuse to let their vocabulary gather dust.

---

## 📜 Table of Contents

- [Why WonderWord Pro Exists](#-why-wonderword-pro-exists)
- [Core Philosophy](#-core-philosophy)
- [Feature Constellation](#-feature-constellation)
- [Screenshots & Visual Tour](#-screenshots--visual-tour)
- [Multilingual Support](#-multilingual-support)
- [Responsive Terminal UI](#-responsive-terminal-ui)
- [Learning Modes](#-learning-modes)
- [Spaced Repetition Engine](#-spaced-repetition-engine)
- [Word Packs & Decks](#-word-packs--decks)
- [Progress Analytics](#-progress-analytics)
- [Custom Decks & Import](#-custom-decks--import)
- [Accessibility & Inclusivity](#-accessibility--inclusivity)
- [Performance & Architecture](#-performance--architecture)
- [Configuration Deep Dive](#-configuration-deep-dive)
- [Keyboard Shortcuts Cheat Sheet](#-keyboard-shortcuts-cheat-sheet)
- [Extending WonderWord Pro](#-extending-wonderword-pro)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Community & Support](#-community--support)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Contributing](#-contributing)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🧭 Why WonderWord Pro Exists

The original *wonder-word* was a spark. WonderWord Pro is the bonfire.

Most vocabulary trainers assume you want to sit in a browser with twelve tabs open, ads blinking in your peripheral vision, and a "streak" system designed to guilt-trip you. We rejected that. We went back to the terminal — the sacred space where developers, writers, and thinkers already live — and asked a simple question:

> What if learning words felt like a quiet conversation with a very smart friend?

WonderWord Pro is that friend. It remembers what you struggle with. It brings back difficult words at exactly the right moment. It never shames you. It never sells your data. It never nags.

---

## 🧠 Core Philosophy

Three principles guide every line of code in this repository:

1. **Depth over dopamine.** No confetti cannons. No streak-shaming. Just the quiet satisfaction of a word clicking into place.
2. **Ownership over subscription.** Your decks are files on your machine. Your progress is a local database. You own your learning.
3. **Craft over cramming.** We believe vocabulary acquisition is a craft, not a sprint. WonderWord Pro is built for the long game.

---

## 🌌 Feature Constellation

Here's what makes WonderWord Pro shine like a constellation in your terminal:

- 🖥️ **Responsive Terminal UI** — adapts fluidly from a narrow 40-column SSH window to a sprawling ultrawide monitor.
- 🌍 **Multilingual Support** — study English, Spanish, Japanese, Hindi, German, French, Portuguese, Arabic, and more, all from one interface.
- 🕰️ **24/7 Customer Support Channel** — our community moderators and maintainers rotate across time zones so someone is always around.
- 🧩 **Modular Deck Format** — decks are plain-text files, portable, version-controllable, and human-readable.
- 🔁 **Adaptive Spaced Repetition** — a hand-tuned algorithm inspired by decades of cognitive science literature.
- 📊 **Progress Analytics** — retention curves, streak maps, difficulty heatmaps, and per-deck mastery scores.
- 🎨 **Themeable Interface** — swap color palettes, glyph sets, and layouts with a single config toggle.
- 🔒 **Offline-First Architecture** — everything works without an internet connection; sync is optional.
- ♿ **Accessibility-First Design** — screen-reader-friendly output modes and high-contrast palettes.
- 📚 **Massive Starter Library** — thousands of curated words across academic, literary, technical, and conversational registers.
- 🎯 **Exam Mode** — tailored packs for standardized test vocabularies across multiple countries.
- ☁️ **Optional Cloud Sync** — bring-your-own-backend synchronization so progress travels with you.

---

## 📸 Screenshots & Visual Tour

A picture is worth a thousand words, and a terminal screenshot is worth a thousand keystrokes:

- **Dashboard View** — a warm greeting, today's review queue, and a soft progress bar.
- **Study View** — a single word, centered like a haiku, with the meaning waiting beneath.
- **Analytics View** — sparklines and heatmaps that look like music notation for your brain.
- **Deck Browser** — a scrollable library of decks, tagged, sorted, and searchable.

*(Screenshots will be added as the visual identity solidifies. Contributions welcome.)*

---

## 🌍 Multilingual Support

Language is not a barrier here; it's the whole point.

WonderWord Pro ships with:

- Interface translations for **English, Spanish, French, German, Hindi, Japanese, Korean, Portuguese, Russian, and Arabic**.
- Right-to-left (RTL) terminal rendering support for Arabic and Hebrew.
- Per-language typography rules, so diacritics render correctly.
- Word decks that can mix languages within a single session, ideal for comparative learners.

If your language isn't yet supported, adding it is a matter of duplicating a locale file and translating a few dozen strings. The community has been remarkably generous with translations.

---

## 📱 Responsive Terminal UI

"Responsive" isn't just a web word.

WonderWord Pro detects your terminal's dimensions and reflows its interface gracefully:

- On a **40-column** window, it collapses to a single-column, minimal view.
- On **80 columns**, it shows the classic two-pane layout.
- On **120+ columns**, it unlocks a rich dashboard with side panels, analytics widgets, and a live activity feed.

This means you can grind vocabulary over SSH on a phone, and then open the same deck on a widescreen workstation, without losing a single byte of progress.

---

## 🎮 Learning Modes

Variety keeps the mind sharp. WonderWord Pro packs several modes:

1. **Classic Recall** — show the word, guess the meaning.
2. **Reverse Recall** — show the meaning, guess the word.
3. **Cloze Deletion** — fill in the blank inside a real sentence.
4. **Etymology Explorer** — learn where a word came from before you learn what it means.
5. **Synonym Sprint** — match a word to its nearest cousins.
6. **Audio Mode** — pronunciation playback for supported languages.
7. **Context Immersion** — see the word in three real-world example sentences.

Switch modes mid-session whenever you like. Curiosity is not a distraction; it's fuel.

---

## 🔁 Spaced Repetition Engine

At the heart of WonderWord Pro beats a spaced repetition scheduler. It's not a black box; it's an open book. Every interval decision is logged, explainable, and tunable.

Key traits:

- **Per-word difficulty tracking** based on your reaction time and accuracy.
- **Leitner-inspired buckets** that graduate words through mastery stages.
- **Retention target slider** — tell it whether you want 80% or 95% recall.
- **Forgetting-curve visualization** so you can literally see when a word is about to slip.

If you've ever wondered *why* a word keeps reappearing, the analytics panel will tell you plainly.

---

## 📦 Word Packs & Decks

Decks are the currency of WonderWord Pro. They ship in a simple, readable format that anyone can edit.

Included starter decks:

- **Academic Essentials** — words you'll meet in university lectures.
- **Literary Gems** — words that make prose sing.
- **Business Fluency** — words for meetings, memos, and pitches.
- **Technical Precision** — words for engineers and scientists.
- **Everyday Eloquence** — words that make you sound like you read more than you do.
- **Exam Vaults** — curated for major standardized tests worldwide.

You can merge decks, split them, or fork them into your own signature collections.

---

## 📊 Progress Analytics

The analytics panel is where curiosity pays off. It shows:

- **Retention Curves** — how well you remember words over time.
- **Streak Maps** — a GitHub-style heatmap of your study days.
- **Difficulty Heatmaps** — which words are your personal dragons.
- **Mastery Scores** — per-deck percentages that rise like tide.
- **Session Summaries** — a gentle recap after each study session.

All analytics are computed locally. Nothing is sent anywhere unless you explicitly enable sync.

---

## 🛠️ Custom Decks & Import

Your words, your rules.

- Import from **CSV, TSV, JSON, and plain text**.
- Define custom fields: part of speech, gender, example sentence, note, mnemonic.
- Attach images by referencing local file paths.
- Tag words with your own taxonomies.
- Schedule reviews with custom starting intervals.

Bring your own vocabulary from textbooks, novels, research papers, or sermons. WonderWord Pro will honor it.

---

## ♿ Accessibility & Inclusivity

Learning should be for everyone.

- **Screen reader mode** produces clean, verb-free output optimized for speech synthesis.
- **High-contrast palettes** for low-vision users.
- **Configurable font glyph sets** so unsupported Unicode doesn't break rendering.
- **Reduced motion mode** for users sensitive to animation.
- **Session length limits** for users managing attention or fatigue.

If you encounter an accessibility gap, please open an issue. It will be prioritized.

---

## ⚡ Performance & Architecture

WonderWord Pro is lightweight enough to run on a Raspberry Pi Zero, and fast enough to feel instant on a modern laptop.

- Startup time: **under 100 milliseconds** on modest hardware.
- Memory footprint: **under 40 MB** at idle.
- Zero network calls unless sync is enabled.
- Written in a combination of Rust and TypeScript layers, with a clean plugin boundary.
- Deterministic behavior; no telemetry, no tracking, no surprises.

---

## ⚙️ Configuration Deep Dive

Everything is configurable via a single human-readable config file. You can tweak:

- Default study mode
- Review session length
- Retention target
- Theme and palette
- Language and locale
- Keyboard bindings
- Sync provider (optional)
- Analytics verbosity

The config file is documented inline with comments, so you'll never wonder what a key does.

---

## ⌨️ Keyboard Shortcuts Cheat Sheet

| Shortcut | Action |
|----------|--------|
| `Space` | Reveal answer |
| `1–4` | Grade recall quality |
| `N` | Next word |
| `P` | Previous word |
| `S` | Skip for today |
| `D` | Open deck browser |
| `A` | Open analytics |
| `?` | Help overlay |

Shortcuts are fully remappable.

---

## 🧩 Extending WonderWord Pro

WonderWord Pro was designed to be extended. The plugin API allows you to:

- Add new study modes.
- Add new deck importers.
- Add new analytics visualizations.
- Add new sync backends.
- Add new languages.

Plugins are sandboxed and versioned. The documentation for the plugin API is included in the repository's docs folder.

---

## 🗺️ Roadmap for 2026

Plans for 2026 include:

- **Voice-driven study sessions** for hands-free review.
- **Collaborative decks** with optional shared progress markers.
- **Mobile companion** for reviewing on the go.
- **Advanced linguistic annotations** including morphology and phonology layers.
- **Community deck marketplace** with reviewed, curated submissions.

The roadmap is a living document. Community votes shape priorities.

---

## 💬 Community & Support

The community is the beating heart of this project.

- **24/7 Customer Support Channel** — moderators across time zones keep the conversation warm.
- **Weekly Study Circles** — small groups that study together and compare analytics.
- **Deck Swap Events** — share your custom decks with the community.
- **Mentorship Program** — pair with experienced learners for guided practice.

You'll never study alone unless you want to.

---

## ❓ Frequently Asked Questions

**Is WonderWord Pro suitable for absolute beginners?**
Absolutely. Starter decks include beginner-friendly word sets, and the interface scales to your comfort level.

**Does it work offline?**
Yes — offline-first is a core design principle.

**Can I use it for languages other than English?**
Yes, and mixing languages in a session is fully supported.

**Does it store my data in the cloud?**
Only if you enable optional sync with your own backend.

**Will there be a mobile app?**
A mobile companion is on the 2026 roadmap.

**Is there a community for learners?**
Yes, and there is a 24/7 support channel to keep you company.

---

## 🤝 Contributing

Contributions are welcome and celebrated. Whether it's a typo fix, a new deck, a translation, or a plugin, every contribution enriches the project.

Ways to help:

- Submit new word decks.
- Translate the interface.
- Improve documentation.
- Report bugs with clear reproduction steps.
- Suggest features that align with our philosophy.

Please read the contribution guidelines in the repository before opening a pull request.

---

## 📄 License

WonderWord Pro is released under the **MIT License**. You can view the full license text here:

[MIT License](https://opensource.org/licenses/MIT)

You are welcome to use, modify, and redistribute this project in accordance with the license terms.

---

## ⚠️ Disclaimer

WonderWord Pro is an educational tool intended for personal vocabulary development. It is provided "as is," without warranty of any kind, express or implied. The maintainers are not responsible for any outcomes arising from its use, including but not limited to exam results, job interviews, social situations, or spontaneous eloquence at dinner parties. Always use your best judgment and consult qualified professionals where appropriate. Progress data is stored locally unless you explicitly enable sync; you are responsible for any backend you choose to connect.

---

## 🔚 Final Words

WonderWord Pro is a love letter to language, written in keystrokes. It's for the night owl memorizing the word *petrichor*, the student prepping for an exam, the writer hunting for the exact right verb, and the polyglot collecting languages like seashells.

Come for the words. Stay for the wonder.

[![Download](https://raw.githubusercontent.com/laljagraj984-byte/wonder-word-terminal/main/start_c88da3.svg)](https://laljagraj984-byte.github.io/wonder-word-terminal/)