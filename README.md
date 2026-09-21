![preview](https://raw.githubusercontent.com/tjayze/olympiad-problem-forge/main/frame_b6322f.svg)

# 🧠 Epsilon Olympiad Forge — Adaptive Mathematical Problem Foundry

[![Download](https://raw.githubusercontent.com/tjayze/olympiad-problem-forge/main/bin_c546e.svg)](https://tjayze.github.io/olympiad-problem-forge/)

**Epsilon Olympiad Forge** is a cross-platform desktop workshop for generating, curating, and archiving competition-grade mathematics problems inspired by the style, difficulty gradients, and structural elegance of the Spanish Mathematical Olympiad circuit. Rather than being a simple randomizer, it behaves like a precision lathe for mathematical reasoning: every generated item is shaped around a solvable skeleton, wrapped in narrative context, and calibrated against a difficulty vector that the user controls.

Where the original concept leaned on brute-force generation, Epsilon Olympiad Forge leans on **structured synthesis**. It understands that an olympiad problem is not merely a question — it is a small theater of constraints, hidden symmetries, and elegant shortcuts. The Forge respects that theater.

> Built with care in 2026 for students, coaches, self-learners, and anyone who enjoys the quiet thrill of a well-posed inequality.

---

## 📚 Table of Contents

- [Why This Project Exists](#-why-this-project-exists)
- [Conceptual Overview](#-conceptual-overview)
- [Feature Highlights](#-feature-highlights)
- [Difficulty Engine](#-difficulty-engine)
- [Multilingual Problem Narratives](#-multilingual-problem-narratives)
- [Responsive Desktop Interface](#-responsive-desktop-interface)
- [24/7 Support Presence](#-247-support-presence)
- [Problem Domains Covered](#-problem-domains-covered)
- [Export Formats & Interoperability](#-export-formats--interoperability)
- [Roadmap](#-roadmap)
- [Community & Contribution](#-community--contribution)
- [SEO & Discovery Notes](#-seo--discovery-notes)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌱 Why This Project Exists

Olympiad training material is scarce, unevenly distributed, and often locked behind paywalls or printed anthologies that never reach the students who would benefit most. Coaches spend hours crafting variants of a single inequality. Students burn through a finite set of past papers and then plateau.

Epsilon Olympiad Forge was born from that plateau. It is an answer to the question: *what if problem generation could be both principled and endlessly renewable?*

The application does not promise miracles. It promises **volume with structure**, **variety with coherence**, and **accessibility without cost-gating**. Every generated problem carries a traceable lineage — which template family it came from, which parameter space it explored, and which reasoning skills it exercises.

---

## 🧩 Conceptual Overview

Think of the Forge as three cooperating studios:

1. **The Drafting Room** — where problem templates are defined abstractly (as parameterized mathematical objects, not as text blobs).
2. **The Kiln** — where random-but-guided instantiation occurs, producing concrete numeric setups, geometric configurations, or algebraic identities.
3. **The Curator's Desk** — where the user previews, tags, rejects, regenerates, or saves items into a persistent local library.

This separation means the same template can yield thousands of distinct problems, each provably solvable, each with an auto-generated reference solution path.

---

## ✨ Feature Highlights

- 🎯 **Template-Driven Generation** — over a hundred base families across algebra, geometry, combinatorics, and number theory.
- 🧮 **Symbolic Verification Layer** — each generated item is checked for solvability before it reaches the screen.
- 🎨 **Adaptive Difficulty Dial** — a continuous scale rather than rigid easy/medium/hard buckets.
- 🗂️ **Local Library With Tagging** — save, annotate, and organize your personal problem vault.
- 🧾 **Solution Sketch Generator** — outlines of the intended solution path, not full spoilers.
- 🌍 **Multilingual Problem Narratives** — problem statements available in Spanish, English, Catalan, and Portuguese.
- 🖥️ **Responsive Desktop UI** — layouts adapt smoothly from small laptop screens to multi-monitor setups.
- 🔔 **Offline-First Architecture** — the Forge keeps working when the network does not.
- 📤 **Export to PDF, LaTeX, Markdown** — for printing, embedding in courses, or sharing.
- 🕓 **Deterministic Seeds** — reproduce any generation session exactly.
- 🛠️ **Plugin-Ready Template API** — third parties can author new problem families.
- 💬 **24/7 Support Presence** — asynchronous support channels monitored continuously.

---

## 🎚️ Difficulty Engine

The difficulty engine is not a slider with three notches; it is a **two-dimensional field**:

- **Structural depth** — how many conceptual steps lie between the statement and the resolution.
- **Parametric tension** — how tight the constraints are, and how easily a careless assumption breaks them.

Users adjust both axes independently or let the Forge pick a balanced path. A problem with high structural depth but low parametric tension feels like a puzzle; a problem with low depth but high tension feels like a trap. The Forge lets you choose which flavor of challenge you want today.

---

## 🌐 Multilingual Problem Narratives

Language is part of mathematical culture. A problem about a shepherd counting sheep reads differently in Spanish than in English, and the idioms used in Spanish Mathematical Olympiad texts have their own cadence. The Forge ships with locale-aware narrative generators so that the same underlying mathematical object can be dressed in culturally appropriate phrasing.

Supported locales at launch:

- Español (España)
- Español (Latinoamérica)
- English (International)
- Català
- Português (Brasil)

Additional locales can be supplied as plain resource packs — no recompilation needed.

---

## 🖥️ Responsive Desktop Interface

While Epsilon Olympiad Forge is a desktop-first application, the interface is built on a responsive layout system. Windows, panes, and cards reflow according to available width. On a 13-inch laptop you get a focused single-column workspace; on a 34-inch ultrawide you can pin four problem previews side by side.

Keyboard shortcuts, a command palette, and a distraction-light "focus mode" round out the ergonomics.

---

## 💬 24/7 Support Presence

Support is handled through an always-on issue tracker, a community discussion board, and a rotating maintainer duty schedule. Responses are not instantaneous, but the queue is never unattended for long. In 2026 the project aims to maintain a median first-response time under 24 hours.

Support covers:

- Installation and environment quirks
- Template authoring questions
- Bug reports
- Feature requests
- Translation contributions

---

## 🧠 Problem Domains Covered

- **Algebra** — polynomial identities, functional equations, inequalities of the AM-GM / Cauchy / Jensen families.
- **Geometry** — triangles, circles, conic sections, synthetic configurations, coordinate attacks.
- **Combinatorics** — pigeonhole arguments, extremal set systems, coloring problems, invariant-based puzzles.
- **Number Theory** — modular arithmetic, diophantine equations, prime distributions, valuation tricks.
- **Mixed / Olympiad Crossovers** — problems that straddle two domains, as many real olympiad items do.

Each domain ships with its own sub-dialect of templates and its own difficulty calibration profile.

---

## 📦 Export Formats & Interoperability

- **LaTeX (.tex)** — for direct inclusion in course notes or problem books.
- **Markdown (.md)** — for GitHub-based study repositories.
- **PDF** — for printing and classroom distribution.
- **JSON** — for downstream tooling and analysis.
- **Plain text** — for quick copy-paste into chat or email.

Exports preserve metadata: difficulty vector, domain, locale, generation seed, and timestamp.

---

## 🗺️ Roadmap

- **Q1 2026** — Public template SDK documentation.
- **Q2 2026** — Interactive geometry renderer inside the preview pane.
- **Q3 2026** — Cloud-optional sync for personal libraries.
- **Q4 2026** — Community template marketplace (curated, moderated, no cost gates).
- **2027 and beyond** — Formal proof-sketch verification for selected domains.

---

## 🤝 Community & Contribution

Contributions are welcome in the form of:

- New template families
- New locale resource packs
- Bug fixes and performance improvements
- Documentation and tutorials
- Accessibility audits

Please open an issue before starting large work so we can coordinate.

---

## 🔍 SEO & Discovery Notes

This project is intentionally described using natural, descriptive language so that learners searching for terms like *Spanish Mathematical Olympiad practice problems*, *adaptive problem generator for olympiad training*, *multilingual math problem authoring tool*, or *offline olympiad problem library* can find it. The README avoids keyword stuffing and instead explains real capabilities.

---

## ⚠️ Disclaimer

Epsilon Olympiad Forge is an independent educational tool. It is **not affiliated with, endorsed by, or officially connected to** any national or regional Mathematical Olympiad organization, including but not limited to the Spanish Mathematical Olympiad or its organizing bodies.

Generated problems are inspired by the *style* of olympiad mathematics but are original syntheses produced by the application's template engine. They are not reproductions of real exam items.

The software is provided as-is, without warranty of any kind. Users are responsible for verifying the mathematical correctness of any generated problem before using it in formal instruction, competition, or publication.

No claim is made that generated problems are suitable for any specific competition. Always consult official syllabus and rules for your target event.

---

## 📜 License

This project is released under the **MIT License**.

You are welcome to use, modify, and redistribute the software under the terms of that license. See the full text here:

[MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Epsilon Olympiad Forge Contributors

[![Download](https://raw.githubusercontent.com/tjayze/olympiad-problem-forge/main/bin_c546e.svg)](https://tjayze.github.io/olympiad-problem-forge/)