# How to store cognitive psychology books legally

GitHub is a versioned text workspace. It is a poor and often illegal place for book binaries.

## Recommended architecture

```text
GitHub repo (this one)
  citations, notes, maps, flashcard *text*, reading paths

Reference manager (Zotero recommended)
  attachments you are allowed to keep (publisher PDF for personal use, your scans of owned print where local law allows)
  better BibTeX / CSL citations

Personal cloud or encrypted drive
  large files, highlights export, OCR

Library systems
  official ebooks, controlled digital lending, interlibrary loan
```

## What you may generally keep here

- ISBNs, DOIs, WorldCat links
- Your original summaries and critiques
- Short quotations with page numbers
- Public-domain texts (e.g., James 1890 in many regions)
- Papers the author or journal has placed under an open license
- Figures you created yourself

## What you should not commit

- Publisher PDFs
- Library downloads that the license restricts to personal use only *and* that forbid redistribution
- Coursepacks
- Scans of books you do not own, shared to a public repo

`.gitignore` in this repo already ignores `*.pdf` and `*.epub` so they are harder to add by accident.

## Practical setup (Zotero + this repo)

1. Install Zotero and the browser connector.
2. Create a collection `Cognitive Psychology`.
3. Store the PDF in Zotero, not in git.
4. Export a citation or citation key into the YAML of your note file.
5. If you use Obsidian, you can git-sync *markdown vault notes* while keeping attachments outside the public remote.

## Finding legal copies

- University / public library catalogs and Libby/OverDrive where available
- Publisher rental or legitimate ebook stores
- Used print (still the most durable edition for heavy annotation)
- PsyArXiv, PubMed Central, author personal pages for *papers*
- Project Gutenberg / Internet Archive for confirmed public-domain books
- Unpaywall / OpenAlex for legal OA versions of articles

## If this repo is private

Privacy does not equal license. A private GitHub repo is still a reproduction and, if anyone else is invited, a distribution. Keep binaries out unless you have rights that clearly cover that use.
