# Contributing

## Scope

Add or improve:

- bibliographic records
- topic maps and concept glossaries
- original study notes
- reading paths
- links to legal open-access versions

Do not add:

- full book files (PDF, EPUB, MOBI, DJVU)
- chapter-length copyrighted extracts
- answer keys or instructor manuals you do not own the rights to publish

## File conventions

- Markdown, UTF-8, one topic or one work per file when possible.
- Book filenames: `notes/author-short-title.md` in lowercase-kebab-case.
- Prefer APA-style citations in body text.
- Keep YAML front matter on notes so the catalog stays parseable.

## Note quality bar

A useful book note answers:

1. What problem was the book written to solve?
2. What is the central model or claim?
3. Which experiments or case studies actually carry the argument?
4. What did later work keep, revise, or reject?
5. Who should read it now, and who can skip it?

## Pull request checklist

- [ ] Citation includes author, year, title, publisher or journal, ISBN or DOI when known
- [ ] No copyrighted full text
- [ ] Topic page updated if the work is a core source for that topic
- [ ] `catalog/catalog.json` updated when you add a major title
