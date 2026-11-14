# Personal Homepage

## Scope
- This repository contains Kouta Nakayama’s personal GitHub Pages website, built with Jekyll.
- Edit publication content in `index.md`, preserving the existing section structure, reverse chronological order, and bold formatting for the site owner’s name.
- Verify publication titles, author order, venue, and year against primary sources. Distinguish Findings papers from main conference papers.
- Do not publish private correspondence, credentials, or unannounced information.

## Verification
- Run `git diff --check` and inspect the changed publication entry.
- Run `bundle exec jekyll build` when the required Ruby dependencies are available; report any build limitation.
- Do not manually edit generated `_site` files for content updates. The existing GitHub Pages workflow builds the site from source.
- Submit requested changes through a pull request; do not merge or push directly to `main` without authorization.
