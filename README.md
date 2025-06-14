# 📖 Bookshelf — A Standard for Structuring Memory

> MIT Licensed, human-first memory structure for agents, tools, and people.

---

## ✨ What is Bookshelf?

> \*"The system helps you connect your **books**, **pages**, **marks**, **ribbons**, and **trails** to create custom **Marker Agents**.

**Bookshelf** is a memory-first, Markdown-native standard for organizing thought, action, and intent. It reimagines the traditional file system as a living, breathing **storybook-style environment** — made of **books**, **pages**, **marks**, **markers**, **ribbons**, and **trails** — where every interaction helps the system construct a memory-aware interface.

It is:

* MIT Licensed, like Storybook, Tailwind, and the best open tools
* Designed to work with `.book`, `.mark`, `.marker`, `.ribbon`, `.trail`, and `.mstp` formats
* UI-agnostic — works in terminal, GUI, markdown viewers, or AR
* Not a book simulator, but a developer storytelling structure — like Storybook, but for logic and memory

---

## 📘 Core Concepts

| Concept       | Folder        | Description                        |
| ------------- | ------------- | ---------------------------------- |
| **Bookshelf** | `.bookshelf/` | A collection of unstructured books |
| **Case**      | `bookcase/`   | A collection of ready to use books |

| Concept  | File    | Description                                             |
| -------- | ------- | ------------------------------------------------------- |
| **MSTP** | `.mstp` | Markdown Storytelling Protocol — system-generated logic |
| **Book** | `.book` | A single point of truth and knowledge                   |

| Concept    | File/Folder           | Description                                   |
| ---------- | --------------------- | --------------------------------------------- |
| **Page**   | `.page`, `pages/`     | A single context snapshot                     |
| **Mark**   | `.marker`, `markers/` | Jump point to a reusable logic chunk          |
| **Marker** | `.mark`, `marks/`     | Identity or memory tied to a function or flow |
| **Ribbon** | `.ribbon`, `ribbons/` | Starting point of a memory flow               |
| **Trail**  | `.trail`, `trails/`   | System-tracked logs for each marker           |

---

## 📂 File Hierarchy Example

```
.bookshelf/
├── bookcase/
│   ├── me.book
│   ├── fed.book
│   ├── elda.book
│   ├── hwy.book
│   ├── eco.book
│   └── openhwy.book
├── marks/
│   ├── scan.mark
│   ├── sign.mark
│   ├── check.mark
│   ├── whisper.mark
│   └── process.mark
├── pages/
│   ├── process-checker.page
│   ├── bugfix-notes.page
│   └── whisper-notes.page
├── ribbons/
│   ├── packet-process.ribbon
│   ├── cargo-setup.ribbon
│   └── whisper-call.ribbon
├── markers/
│   ├── me.marker
│   ├── packet-pilot.marker
│   ├── cargo-connect.marker
│   └── whisper-witness.mark
├── trails/
│   ├── packet-pilot.trail
│   ├── cargo-connect.trail
│   └── whisper-witness.trail
├── book.mark
├── mark.trail
└── mark.mstp
```

---

## 🧠 Why Bookshelf?

This is not a `.mark` or `.marker` generator — that’s what **MARK CLI** does.

Instead, Bookshelf is:

* A Storybook-style interface for linking your **marks** to your **markers** logic
* A runtime interface for building and following **marker flows**
* A shared environment where markers trigger agent actions or self-navigation
* A context-driven tool where adding a `.book`, `.page`, `.mark`, `.marker`,`.ribbon`, or `.trail` wires it into the system automatically

All you have to do is:

* Write `packet-scanner.mark.ts` alongside `packet-packet.ts`
* Write `packet-pilot.marker.py` alongside `packet-pilot.py`
* Write `packetView.page.tsx` alongside `packetView.tsx`
* Write `packet-process.ribbon.py` alongside `packet-process.py`
* Add `fed.book` — and Bookshelf will render it into your own custom `mark.trail`

Note: **Trails** can be added to any `.marker` inside the `.bookshelf/` to trail each markers use.

The system connects your books and pages together, creates a visual Bookshelf interface, and dynamically builds marks, markers, trails, books, pages, ribbons, and MSTP records as you go.

---

## 💪 Usage

```
# Open a books interface like Storybook
bookshelf open <*.book>

# Open a bookcase interface like Storybook
bookshelf open bookcase
```

---

## 📖 Example Use Cases

* Link `.mark` and `.marker` files to build agent behaviors
* Add `.book` files to connect workflows and trails
* Watch your MSTP trail grow automatically as you work
* Run in dev, test, or production to see memory-based linking and flow in action

---

## 📜 License

MIT License — because memory belongs to everyone.

Use it. Fork it. Tell your story.

---

## 💬 Credits

Originally envisioned by **Jesse Conley**
Built to help truckers, builders, and humans remember who they are
Structured by the MARK OS protocol and Storybook-style logic flow

> “Show me someone’s Book, and I’ll tell you who they are.”

---

## ✍️ Author

**Jesse Edward Eugene Wayne Conley**

* 📬 [jesse.freightdev@gmail.com](mailto:jesse.freightdev@gmail.com)
* 🔗 [github.com/freightdev](https://github.com/freightdev)

> "I didn’t build this to automate the road. I built it so no one gets left behind."

---

## 💛 Support

If this project helps you or inspires your agent builds:
[Buy Me a Coffee](https://coff.ee/freightdev)

Every dollar goes toward tools for the ones still behind the wheel.

☕️ Jesse — [freightdev](https://github.com/freightdev)
