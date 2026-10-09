# Zhimin Li academic website

Personal academic website built from the [Academic Pages template](https://github.com/academicpages/academicpages.github.io). The site uses Jekyll and GitHub Pages.

## Content

- Homepage: `_pages/about.md`
- Research: `_pages/research.md`
- Publications: one Markdown file per paper in `_publications/`
- CV: `_pages/cv.md`
- Navigation: `_data/navigation.yml`
- Personal profile and links: `_config.yml`

The homepage portrait uses `images/zhimin-li.jpg`. To change it, replace that image or update `author.avatar` in `_config.yml`.

Two manuscripts under blind review are listed as "Under review" with internal detail pages. Their PDFs are not included.

## Publishing

This site is configured for the `Krisocer/Krisocer.github.io` repository and the `https://krisocer.github.io` address. GitHub Pages builds the site from the repository's default branch.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## Source and license

This site retains the upstream [Academic Pages](https://github.com/academicpages/academicpages.github.io) code and its MIT license in `LICENSE`.
