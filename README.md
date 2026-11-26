# Aditya Jain — Personal Website

Personal website built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).
Design adapted from [Sriram Narayanan's site](https://github.com/nnsriram97/nnsriram97.github.io) (MIT licence; see `LICENSE`).

## Edit content

- Bio, news and the PhD call-out: `index.md`
- Research entries: `_data/research.yml`
- Projects: `_data/projects.yml`
- Experience row: `_data/experience.yml`
- Name, links, CV path: `_config.yml` (`owner.cv: /files/cv.pdf` shows the CV button)

## Local preview

```bash
docker run --rm -v "$PWD":/srv -w /srv -p 4000:4000 ruby:3.3 \
  sh -c "bundle install && bundle exec jekyll serve --host 0.0.0.0"
```
