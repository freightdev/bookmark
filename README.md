# 📖 Bookmark — A Standard for Structuring Memory

> *"The system will write the tale — to help you tell your story."*
> MIT Licensed, human-first memory structure for agents, tools, and people.

---

## ✨ What is Bookmark?

**Bookmark** is a memory-first, Markdown-native standard for organizing thought, action, and intent.
It reimagines the traditional file system as a living, breathing **book** — made of **pages**, **marks**, **ribbons**, and **trails** — where every action becomes part of your evolving story.

It is:

* MIT Licensed, like Storybook, Tailwind, and the best open tools
* Designed for people, tools, and AI agents
* UI-agnostic — works in terminal, GUI, markdown viewers, or AR
* Built on plain files: `.mark`, `.bookmark`, `.book`, `.trail`, `.page`, `.tale`

---

## 📘 Core Concepts

| Concept       | File/Folder                 | Description                                          |
| ------------- | --------------------------- | ---------------------------------------------------- |
| **Book**      | `.book`, `~book/`           | A collection of memory, story, or flow               |
| **Page**      | `.page`, `~page/`           | A single view, moment, or memory state               |
| **Bookmark**  | `.bookmark`                 | A jump point to a Page, Ribbon, or Trail             |
| **Mark**      | `.mark`, `~mark/`           | A named memory — can be left by others               |
| **Marker**    | `.marker/`                  | Atomic logic unit or logic pattern                   |
| **Ribbon**    | `.ribbon`                   | A personal journey — the start of a memory path      |
| **MARKTrail** | `.trail`, `marktrail.trail` | A recorded path through memory — story as system log |
| **Tale**      | `.tale/`                    | System-level memory, not user editable               |
| **Shelf**     | `~shelf/`                   | Book storage — active, archived, or synced           |

---

## 📂 File Hierarchy Example

```
~shelf/
├── packetpilot.book
│   ├── page/
│   │   ├── dispatch-log.page
│   │   ├── bugfix-notes.page
│   ├── mark/
│   │   └── login-failure.mark
│   └── marker/
│       └── auth-check.marker
├── marktrail.trail
├── startup.ribbon
└── main.bookmark
```

---

## 🧠 Why Bookmark?

Traditional file systems simulate **filing cabinets**.
**Bookmark** simulates **living memory**.

* Pages remember where you were.
* Bookmarks guide you back.
* Ribbons tell you what mattered.
* MARKTrail shows you how you got here.

---

## 🔁 MARK Kernel

**MARK** stands for **Memory Aware Reference Kernel**.
It routes memory like a story engine, indexing Pages, binding Markers, and stitching your Trails.

---

## 🛠 Usage

```
mark open my.bookmark
marktrail follow ./ribbons/startup.ribbon
bookmark render --to html
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
