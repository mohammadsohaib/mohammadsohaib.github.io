# mohammadsohaib.github.io

Source for [mohammadsohaib.github.io](https://mohammadsohaib.github.io), the personal academic website of Mohammad Sohaib (PhD candidate, ETH Zurich & Paul Scherrer Institut).

Built with Jekyll on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template (a fork of Minimal Mistakes, MIT licensed — see `LICENSE`). GitHub Pages builds and deploys the site automatically from the `master` branch.

## Where things live

| What | File |
| --- | --- |
| Home / About | `_pages/about.md` |
| Research | `_pages/research.md` |
| Publications | `_pages/publications.md` (entries go in `_publications/`) |
| CV page | `_pages/cv.md` (PDF in `files/`) |
| Blog posts | `_posts/YYYY-MM-DD-title.md` |
| Top menu | `_data/navigation.yml` |
| Name, bio, sidebar links, SEO | `_config.yml` |
| Profile photo / icons | `images/` |
| Colours and fonts | `_sass/_variables.scss` |

## Run locally

```bash
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Then open http://localhost:4000. Changes to `_config.yml` need a server restart.
