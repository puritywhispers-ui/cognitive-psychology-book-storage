# Cognitive Psychology Book Storage

A structured GitHub knowledge base for **cognitive psychology**: curated books, classic papers, topic maps, and personal-note templates.

This repository is a *library index and study workspace*, not a pirate archive. It stores metadata, reading paths, concept maps, and your own notes. It does **not** store copyrighted full-text books or scanned PDFs.

**Repo:** [puritywhispers-ui/cognitive-psychology-book-storage](https://github.com/puritywhispers-ui/cognitive-psychology-book-storage)

---

## What this repo is for

- Keep a durable catalog of textbooks, monographs, and public-facing books.
- Organize the field by topic (attention, memory, perception, language, reasoning, etc.).
- Capture *your* notes, quotes you are allowed to keep, and links to legal copies (library, publisher, open access).
- Track a reading path from introductory surveys to primary sources.
- Store summaries of public-domain or openly licensed papers and your original commentary.

## What this repo is not for

- Uploading publisher PDFs, ePub files, or photocopied chapters you do not have rights to share.
- Reconstructing substantial copyrighted text.
- Course-pack dumps of other people's lecture slides unless you own or have license for them.

If you own a book, keep the file in your personal cloud, reference manager (Zotero/Obsidian), or university library locker, and link the citation here.

---

## Repository map

```text
.
├─ README.md
├─ LICENSE
├─ CONTRIBUTING.md
├─ catalog/
│   ├─ textbooks.md          Core academic textbooks
│   ├─ popular-and-crossover.md
│   ├─ classics.md           Foundational books that defined the field
│   ├─ papers.md             Landmark papers (legal / bibliographic)
│   └─ catalog.json          Machine-readable index
├─ topics/
│   ├─ attention.md
│   ├─ memory.md
│   ├─ perception.md
│   ├─ language.md
│   ├─ reasoning-and-decision.md
│   ├─ learning-and-expertise.md
│   └─ cognitive-neuroscience.md
├─ notes/
│   ├─ _template-book.md
│   ├─ _template-paper.md
│   └─ examples/
├─ paths/
│   ├─ beginner.md
│   └─ graduate.md
└─ resources/
    ├─ how-to-store-books-legally.md
    └─ tools.md
```

## Suggested reading paths

| Goal | Start here |
| --- | --- |
| First serious survey | `paths/beginner.md` then Eysenck & Keane or Goldstein |
| History of the cognitive revolution | Neisser (1967), Gardner *The Mind's New Science*, Miller 1956 |
| Memory | Baddeley; Schacter; Tulving papers |
| Judgment and decision making | Kahneman *Thinking, Fast and Slow*; Tversky & Kahneman papers |
| Language | Pinker *The Language Instinct*; classic Chomsky / psycholinguistics |
| Vision / perception | Marr *Vision*; Gibson; modern cognitive neuroscience texts |
| Computational / architecture | Anderson ACT-R; Newell & Simon; connectionist readers |

## How to add a book note

1. Copy `notes/_template-book.md`.
2. Name it `notes/surname-short-title.md` (example: `notes/kahneman-thinking-fast-slow.md`).
3. Fill bibliographic data, your rating, 5–7 key claims, and *short* quotations only.
4. Link the note from the matching file in `catalog/` and `topics/`.

## Legal and ethical baseline

- Cite authors and years.
- Quote sparingly (brief excerpts for commentary, study, or review).
- Prefer DOI / ISBN / WorldCat / publisher links over file dumps.
- Public-domain works (older James, some classics) can be linked from Project Gutenberg, Internet Archive *public-domain* scans, or similar.
- When in doubt, store only the citation and your original notes.

## Status

Scaffold created 2026-09-11 as a working library for personal study and sharing of *structure*, not of copyrighted binaries.
