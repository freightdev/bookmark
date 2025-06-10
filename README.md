# 📖 Bookmark — A Standard for Structuring Memory

> *"The system will write a book — to help you tell your tale."*
> MIT Licensed, human-first memory structure for agents, tools, and people.

---

## ✨ What is Bookmark?

**Bookmark** is a memory-first, Markdown-native standard for organizing thought, action, and intent.
It reimagines the traditional file system as a living, breathing **book** — made of **pages**, **marks**, **ribbons**, and **trails** — where every action becomes part of your evolving story.

It is:

* MIT Licensed, like Storybook, Tailwind, and the best open tools
* Designed for people, tools, and AI agents
* UI-agnostic — works in terminal, GUI, markdown viewers, or AR
* Built on plain files: `.bookmark`,`.mark`, `.marker`, `.book`, `.page`, `.mstp`, `.trail`, `.ribbon`

---

## 📘 Core Concepts

| Concept   | Folder   | Description                                       |
| --------- | -------- | ------------------------------------------------- |
| **Shelf** | `shelf/` | Mounting Point for any book                       |
| **Book**  | `book/`  | User-level memory, not system editable by default |

| Concept  | File    | Description                                         |
| -------- | ------- | --------------------------------------------------- |
| **MSTP** | `.mstp` | MARK Story Telling Protocol — a system-level format |

| Concept      | File/Folder               | Description                                     |
| ------------ | ------------------------- | ----------------------------------------------- |
| **Bookmark** | `.bookmark`, `bookmarks/` | A jump point to a specific stopping point       |
| **Page**     | `.page`, `pages/`         | A single view, moment, or memory state          |
| **Mark**     | `.mark`, `marks/`         | A marked memory in your story or tale           |
| **Marker**   | `.marker`, `markers/`     | Atomic logic unit or logic pattern              |
| **Ribbon**   | `.ribbon`, `ribbons/`     | A start of a memory path                        |
| **Trail**    | `.trail`, `trails/`       | A recorded path through memory — aka system log |

---

## 📂 File Hierarchy Example

```
~shelf/
└── book/
    ├── trails/
    │   ├── packet-pilot.trail
    ├── ribbons/
    │   ├── packet-pilot.ribbon
    ├── pages/
    │   ├── packet-process.page
    │   ├── bugfix-notes.page
    ├── bookmarks/
    │   ├── packet-pilot.bookmark
    ├── marks/
    │   └── packet-pilot.mark
    ├──  markers/
    │   ├── packet-scanner.marker
    └── book.mstp
```

---

## 🧠 Why Bookmark?

Traditional file systems simulate **filing cabinets**.
**Bookmark** simulates **living memory**.

* Pages tell you what mattered.
* Bookmarks guide you back.
* Ribbons remember where you started.
* Trails show you how you got here.
* MSTP tells the story of the book.

---

## 🔁 MARK Kernel

**MARK** stands for **Memory Aware Reference Kernel**.
It routes memory like a story engine, indexing Pages, binding Markers, and stitching your Trails.

---

## 🛠 Usage

```
# Open a bookmark into a page
mark open packet-pilot.bookmark

# Follow a recorded ribbon
marktrail follow startup.ribbon

# Export MSTP trail to plain markdown
marktrail export book.mstp --to markdown
```

---

## 📖 Example Use Cases

* Build UI agents using `.mark` files
* Create personal knowledge bases with `.book`
* Teach AI systems with `.trail`-based replay logs
* Document mental health, artistic journeys, software debugging, and dispatch operations

---

## 📜 License

MIT License — because memory belongs to everyone.

Use it. Fork it. Tell your story.

---

## 💬 Credits

Originally envisioned by **Jesse Conley**
Built to help truckers, builders, and humans remember who they are
Structured by the MARK OS protocol and BookOS design

> “Show me someone’s Book, and I’ll tell you who they are.”
