# adi1357.github.io

Personal website of Aditya Jain, built with [Jekyll](https://jekyllrb.com/) on GitHub Pages.

## Edit content

- About text, news and the "open to" note: `index.md`
- Research: `_data/research.yml`
- Projects: `_data/projects.yml`
- Experience: `_data/experience.yml`
- Honors and leadership: `_data/honors.yml`
- Name, links, CV path: `_config.yml` (`owner.cv: /files/cv.pdf` adds a CV link)

Styles are plain CSS in `assets/css/main.css`. Light and dark themes follow the system setting.

## Local preview

```bash
docker run --rm -v "$PWD":/srv -w /srv -p 4000:4000 ruby:3.3 \
  sh -c "bundle install && bundle exec jekyll serve --host 0.0.0.0"
```
