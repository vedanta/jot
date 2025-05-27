# JOT — Journey of Thought

**JOT** is a lightweight, local-first personal knowledge base built using Jupyter Notebooks and VSCode — like Notion, but offline, customizable, and code-native.

---

## ✨ What is JOT?

JOT stands for **Journey of Thought** — a structured system for managing your ideas, notes, journals, projects, and research using:

- 📓 **Jupyter Notebooks** for flexible writing and thinking
- 🧠 **VSCode** as your PKM shell with a clean sidebar UI
- ⚙️ A well-defined folder structure with Git-aware design
- 🚫 `.local` folders for personal content that stays private

JOT is for builders, tinkerers, and thinkers who want a system they fully own — no vendor lock-in, just your thoughts and tools.

---

## 💡 Why JOT?

Notebooks aren't just for code — they’re perfect for organizing ideas that evolve.

JOT combines the **visual clarity of Notion**, the **power of markdown**, and the **local-first trust of Git** into a workspace you can grow over time.

Use it to:
- Journal your daily thinking
- Capture ideas and project notes
- Track interview prep or research
- Build a searchable, extensible knowledge base

---

## 📁 Folder Structure (Phase 1)

```plaintext
.
├── HOME.ipynb                # Main dashboard
├── Templates/                # Note and journal templates
├── Projects/                 # Public project notes
├── Notes/.local              # Personal notes (not tracked by Git)
├── Journal/.local            # Private journals
├── Interviews/.local         # Interview prep (local-only)
├── Assets/                   # Images, headers
├── .vscode/                  # VSCode settings for consistent UX
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Workspace

```bash
git clone https://github.com/your-username/jot.git
cd jot
code jot.code-workspace
```

### 2. Launch Your Dashboard

Open `HOME.ipynb` — this is your main control panel.

### 3. Create Notes or Journals

- Use templates from `Templates/`
- Save personal content under `.local` folders like `Notes/.local`, `Journal/.local`

### 4. Keep Content Local-Only

- **Any folder named `.local/` is ignored by Git** (see `.gitignore`)
- Store anything private there (e.g., personal notes, prep, journals)
- You can safely push the rest to GitHub

---

## 🛤️ Roadmap

| Phase | Feature | Status |
|-------|---------|--------|
| 1.1   | Folder structure, VSCode settings         | ✅ Complete |
| 1.2   | Note templates, collapsible markdown, UI polish | 🚧 In Progress |
| 2.0   | Tags, search, `/commands`, `@`-linking    | 🧠 Planned |
| 3.0   | Full JupyterLab sidebar extension         | 🔮 Future |

---

## 🧠 Philosophy

Think in notebooks, not scattered documents.
Code and prose live together.
Local-first. Yours to shape.

---

## 🛠️ Built With

- [Jupyter](https://jupyter.org/)
- [VSCode](https://code.visualstudio.com/)
- Markdown + plain text
