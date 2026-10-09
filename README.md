# keely-ai.github.io

Source for [Xinyue Ai's homepage](https://keely-ai.github.io/), built with Jekyll and served by GitHub Pages. Pushing to `main` redeploys the site in a minute or two.

## Where things live

| What | File |
| --- | --- |
| Bio, News, Honors, Education, Misc | `_pages/about.md` |
| Publications | `_data/publications.yml` (field reference at the top of the file) |
| Sidebar profile and links | `author:` in `_config.yml` |
| Top navigation | `_data/navigation.yml` |
| Styles, colors, light/dark themes | `assets/css/main.scss` |
| Images | `images/` |

To add a news item, copy an existing line in `_pages/about.md`:

```markdown
- <span class="date">Oct 2026</span> Something happened!
```

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

Originally based on [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) (MIT, see `LICENSE`).
