# JayCho01.github.io

Personal academic website of **Junhyeon Cho** — M.S. student in Robotics at Dongguk University, Interactive Robotics Lab (Prof. Soo-Chul Lim).

🔗 https://JayCho01.github.io

Built with [Jekyll](https://jekyllrb.com/) on the
[AcademicPages](https://github.com/academicpages/academicpages.github.io) template and hosted on GitHub Pages.

## Content

- `_config.yml` — site configuration (name, bio, social links)
- `_pages/about.md` — homepage (intro + publications + projects + awards + blog)
- `_publications/` — publication entries
- `_data/` — site data (navigation, author, CV)
- `images/`, `files/` — assets (profile photo, papers, figures, CV)

## Local preview

```bash
bundle install
bundle exec jekyll serve --livereload
# open http://localhost:4000
```

## Deploy (GitHub Pages)

1. Create a repository named `JayCho01.github.io`.
2. Push this folder's contents to the `main` (or `master`) branch.
3. Settings → Pages → Source: *Deploy from a branch* → `main` / root.
4. The site builds automatically at https://JayCho01.github.io
