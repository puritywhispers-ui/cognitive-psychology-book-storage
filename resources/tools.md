# Tools that pair with this library

## Citation and files

- **Zotero** — first choice for academic PDFs and citations.
- **Paperpile / EndNote / Mendeley** — fine if you already live there.
- **Obsidian** — local markdown vault; can mirror `notes/` from this repo.

## Spaced retrieval

- **Anki** — put *constructs, contrasts, and named experiments* on cards, not page-long summaries.
- Card pattern: front = "encoding specificity vs. transfer-appropriate processing"; back = contrast + one example + one citation.

## Reading

- **Hypothesis** or native PDF highlighter — export only *your* notes back into markdown.
- **Semantic Scholar / Google Scholar / OpenAlex** — citation chaining.
- **Connected Papers / Inciteful** — map a literature around one seed paper.

## Methods helpers

- A short SDT explainer you trust
- Jamovi or R for when you start reading result sections seriously
- A replication-database habit: check [Curate Science](https://curatescience.org/) / psych-replication trackers before treating a famous effect as a law

## Git workflow for notes

```bash
git clone https://github.com/puritywhispers-ui/cognitive-psychology-book-storage.git
cd cognitive-psychology-book-storage
cp notes/_template-book.md notes/goldstein-cognitive-psychology.md
# write the note
git add notes/goldstein-cognitive-psychology.md catalog/textbooks.md
git commit -m "Add Goldstein textbook note"
git push
```

Keep binaries out of the clone you push to GitHub.
