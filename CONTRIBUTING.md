# Contribution Guidelines

Thanks for wanting to make this list better! Pull requests for new entries, fixes and improvements are all welcome.

## What belongs here

- **Personal bookshelves** — a public page where a person lists the books they've read or recommend. The person should be someone at least a niche audience finds interesting, and the list should have some substance (not three books from 2014).
- **Community and topic lists** — well-maintained lists of books on a topic (a GitHub repo, a site, a long-running page).
- **Discovery sites** — sites whose main job is helping people find books through recommendations from real people.
- **Curated lists in this repo** — if someone notable doesn't maintain their own list (e.g. Warren Buffett), you can compile one in `lists/` — but **every book must have a source** (an interview, letter, or post where they actually recommended it).

## What doesn't belong

- Dead or parked pages, or pages that no longer contain a reading list.
- Pure storefronts, affiliate-link farms, or algorithmic "top 100 books" SEO pages.
- Self-promotion of a list with no track record (give it some substance first).

## Entry format

Add entries to the fitting section, keeping **alphabetical order** (by first name for people):

```markdown
- [Person or Site Name ↗](https://example.com/books) - One short sentence saying what makes this list worth reading.
```

- External links get a ` ↗` at the end of the link text; links to files inside this repo (like the curated lists) don't.
- Descriptions start with a capital letter and end with a period.
- Prefer `https://` and link directly to the reading-list page, not the site's homepage.
- Check that the link actually loads before submitting (CI runs a link check too).

## Fixing broken links

Link-rot fixes are the most valuable small PRs. If a list moved, update the URL; if it's gone for good, remove the entry (mention in the PR if an archive.org copy exists, so we can decide whether the entry is worth keeping as an archive link).
