# Contributing

Thanks for helping keep this list useful. The goal is a short list of **reputable, free** places to list a personal brand, not every profile site on the internet.

## How to suggest a site

1. Fork this repository and create a branch.
2. Add one entry to the right category in `README.md`, in alphabetical order.
3. Open a pull request and fill in the template, including how the site meets each criterion below.
4. Send one site per pull request so each one can be reviewed on its own.

If you're not sure a site fits, open an issue first and ask.

## Quality criteria

A site is added only if it meets all of these:

- **SEO bar.** The domain is in the [Tranco](https://tranco-list.eu) top 1M or the [Majestic Million](https://majestic.com/reports/majestic-million). Public profile or listing pages can be indexed: robots.txt doesn't block them, and a sample profile has no `noindex` meta tag or `X-Robots-Tag` header. Include the rank and the sample profile URL you checked in your pull request.
- **Free.** Listing is free, or a real free tier exists. Trial-only and paid-only sites don't qualify.
- **Real moderation and audience.** People review profiles or submissions, or the site has clear community rules, and real users, readers, journalists or buyers visit it. A site that is mainly a backlink source doesn't qualify.
- **Live and active.** The homepage and the signup or submit page load, and the site shows activity within the last six months.
- **Safe content.** No gambling, casino or adult listings, and no injected spam links.

## Entry format

```markdown
- [Site Name](https://example.com) - **Free**. One-line neutral description, plus any requirement or approval wait. [Sign up](https://example.com/signup) _Links: Nofollow._
```

- Pricing must be **Free** or **Freemium** (free tier plus paid options).
- Keep the note to one or two factual sentences. No marketing language, no superlatives you can't back up, and no traffic or DR claims.
- Add the `[Sign up](...)` link only when it differs from the homepage.
- Add `_Links: Dofollow._` or `_Links: Nofollow._` only if you checked the link on a real public profile. Otherwise leave it out.
- Use the site's homepage, not an affiliate or referral link.

### Expert-source and press-query sites

These sites only belong in **Expert-source & press-query sites**. Links come from the articles that quote you, not from a profile, so say "coverage not guaranteed" where it applies.

## What gets rejected

- Sites that sell DR, backlinks or guaranteed SEO value, or that advertise a do-follow backlink as the main reason to list.
- Badge-swap or link-exchange directories, where a free listing requires a badge or a link back.
- Sites whose profile pages are blocked from search engines (`noindex` or a robots.txt disallow).
- Unranked domains (outside both the Tranco top 1M and the Majestic Million).
- Thin, auto-generated or scraped directories.
- Sites with gambling, casino or adult content, or spam listings.
- Dead, parked, merged, redirected-away or stale sites.
- Duplicates of an existing entry, including services run by the same company.
- Self-promotion of a site you own, unless it clearly meets every criterion above. Disclose any affiliation in your pull request.

Entries can be removed later if a site stops meeting these criteria.
