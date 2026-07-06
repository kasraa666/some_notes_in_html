# 📚 some_notes_in_html

> **AI-powered academic knowledge base** — exam review notes & literary reading summaries, built as self-contained, browser-ready HTML pages.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Pages](https://img.shields.io/badge/HTML-100%25-orange)](https://github.com/kasraa666/some_notes_in_html)
[![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen)]()

---

## ✨ Why This Exists

I built this repository to solve a real problem: **organizing dense university course materials into clean, searchable, visually structured review pages** — and doing it at scale with AI assistance.

Instead of scattered Word docs or handwritten notes, every subject here is a **self-contained `.html` file** that you can open in any browser — no build step, no framework, no toolchain. Just double-click and study.

---

## 🧠 What's Inside

| # | Subject | Files | Coverage |
|---|---------|-------|----------|
| 📝 | **Persian Writing** (波斯语写作) | 3 | Structure, linking expressions, genre templates |
| 🇮🇷 | **Political Economy of Modern Iran** | 1 | Full book analysis (Katouzian, 1926–1979) |
| 🕌 | **Concise Islamic Law** (简明伊斯兰教法) | 1 | Complete Hanafi fiqh summary (59 chapters) |
| 🏛 | **Mao Zedong Thought** (毛概) | 4 | Chapter notes, exam bank, past papers, thematic review |
| 🌏 | **PRC Foreign Relations** (新中国对外关系) | 7 | Notes, glossary, essay prep, self-check, exam bank |
| 📜 | **History of Chinese Foreign Relations** | 6 | Course summary, glossary, past exams, question bank |
| 🇨🇳🤝🇺🇸 | **China–US Economic Relations** (中美经贸) | 6 | Outline, key points, glossary, mock exams, essay prep |

**24 files · 7 subjects · 100% self-contained HTML**

---

## 🚀 How to Use

```bash
# 1. Clone the repo
git clone https://github.com/kasraa666/some_notes_in_html.git

# 2. Open any file in your browser
open 波斯语写作复习汇编-第1页.html     # macOS
start 波斯语写作复习汇编-第1页.html    # Windows
```

Or **browse directly on GitHub** — click any `.html` file, then click the "Raw" button to view it rendered.

> 💡 **Tip**: Each page is fully self-contained. CSS is embedded. No internet needed. Works offline perfectly.

---

## 🤖 AI-Assisted Workflow

This entire repository was built with a **human-in-the-loop AI pipeline**:

```
Raw Course Notes / Books
        │
        ▼
┌─────────────────────────┐
│  AI Content Extraction  │  ← LLM parses raw materials into structured outlines
└─────────────────────────┘
        │
        ▼
┌─────────────────────────┐
│  AI Page Generation     │  ← LLM generates clean HTML with embedded CSS
└─────────────────────────┘
        │
        ▼
┌─────────────────────────┐
│  Human Review & Edit    │  ← I verify accuracy, fix errors, refine layout
└─────────────────────────┘
        │
        ▼
   ✅ Final .html page
```

This turns what would be **hours of manual formatting** per page into a ~15-minute review cycle, while keeping me in control of correctness.

---

## 🎨 Design System

Every page shares a consistent visual language:

- **Gradient headers** — subject-specific color palettes for visual navigation
- **Card-based layout** — key concepts rendered as responsive info cards
- **Two-column TOC** — wide tables of contents that collapse to single column on mobile
- **Code blocks** — Persian/Arabic terminology displayed in styled monospace
- **Mobile-first** — `@media (max-width: 640px)` breakpoints on all pages
- **Print-friendly** — clean layouts that render well on paper

---

## 🗂️ Repository Structure

```
some_notes_in_html/
│
├── README.md                          ← You are here
├── LICENSE                            ← MIT
│
├── 📝 Persian Writing
│   ├── 波斯语写作复习汇编-第1页.html   ← Structure & linking expressions
│   ├── 波斯语写作复习汇编-第2页.html   ← Topic-specific vocabulary
│   └── 波斯语写作复习汇编-第3页.html   ← Genre templates
│
├── 🇮🇷 Iranian Studies
│   ├── 现代伊朗的政治经济学_研读解析.html  ← Katouzian book analysis
│   └── 简明伊斯兰教法总结.html             ← Hanafi fiqh summary
│
├── 🏛 Mao Zedong Thought (毛概)
│   ├── 毛概-复习资料.html
│   ├── 毛概-考试题库.html
│   ├── 毛概-真题解析.html
│   └── 毛概-主题串讲复习.html
│
├── 🌏 PRC Foreign Relations (新中国对外关系)
│   ├── 新中对外-复习资料.html
│   ├── 新中对外-考试题库.html
│   ├── 新中对外-论述题专题复习.html
│   ├── 新中对外-名词解释手册.html
│   ├── 新中对外-知识点自查清单.html
│   ├── 新中对外-主题串讲复习.html
│   └── 新中对外-L9-L13知识总结.html
│
├── 📜 History of Chinese Foreign Relations (中国对外关系史)
│   ├── 中国对外关系史_课程总结.html
│   ├── 中国对外关系史-考试题库.html
│   ├── 中国对外关系史-名词解释手册.html
│   ├── 中国对外关系史-真题及参考答案.html
│   ├── 中国对外关系史-知识点自查清单.html
│   └── 中国对外关系史-主题串讲复习.html
│
└── 🇨🇳🤝🇺🇸 China–US Economic Relations
    └── 中美经复习/
        ├── 中美经贸关系复习提纲.html
        ├── 中美经贸关系_考前重点串讲.html
        ├── 中美经贸关系_名词解释手册.html
        ├── 中美经贸关系_模拟题库.html
        ├── 中美经贸关系_知识点自查清单.html
        └── 中美经论述题 史诗级加强.html
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Content** | Pure HTML5 + Embedded CSS3 |
| **AI Pipeline** | LLM Prompt Engineering (structured extraction → page generation) |
| **Version Control** | Git + GitHub |
| **License** | MIT |

No JavaScript frameworks. No build tools. No dependencies. Just HTML files that work everywhere, forever.

---

## 📄 License

MIT — see [LICENSE](LICENSE) for details.

---

## 🙋‍♂️ Author

**Xie Kesai** — undergraduate at Peking University (Persian Language & Literature + International Politics).

- 🔗 GitHub: [@kasraa666](https://github.com/kasraa666)
- 📧 Email: xiekesai@stu.pku.edu.cn

---

<p align="center">
  <sub>Built with 🤖 + ☕ · Last updated July 2026</sub>
</p>
