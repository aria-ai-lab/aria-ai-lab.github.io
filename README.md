# ARIA — Agency · Reasoning · Intelligence · Autonomy

Public website for the **ARIA research lab** at Peking University, served with
GitHub Pages + Jekyll at <https://aria-ai-lab.github.io>.

## Run locally

```bash
bundle install        # first time only
bundle exec jekyll serve
# → http://localhost:4000
```

## Edit content (no HTML needed)

All content lives in `_data/*.yml`:

| File                     | Controls                                                      |
| ------------------------ | ------------------------------------------------------------ |
| `_data/pillars.yml`      | The four ARIA directions on the home page                    |
| `_data/banner.yml`       | The running highlights banner (image + caption)              |
| `_data/news.yml`         | The "Latest news" list (newest by `date`)                    |
| `_data/people.yml`       | People, grouped: faculty → technical_staff → interns → collaborators |
| `_data/publications.yml` | Publications, newest first by `year`                         |

Each person takes `name, role, affiliation, avatar, email, homepage, github,
scholar` — any link may be omitted and its icon disappears. Each publication
takes `title, authors, venue, year, teaser, image` and a `links` map with any of
`pdf, supplementary, poster, project, dataset, code`.

Images go under `assets/img/` (`people/` for avatars, referenced by absolute
path like `/assets/img/people/name.jpg`). Anything missing falls back to a
staff-motif placeholder.

## Design

Brand tokens and structure are documented in `CLAUDE.md`. The logo is a reusable
Liquid include (`_includes/wordmark.html`); colors are CSS variables in
`assets/css/style.css`, which drives both light and dark themes.
