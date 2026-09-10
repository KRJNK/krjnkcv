# krjnkcv

Source for my personal CV/resume, published via GitHub Pages.

**Live site:** https://krjnk.github.io/krjnkcv

Built with [Jekyll](https://jekyllrb.com/) using the
[jekyll-cv-crafter](https://github.com/streetturtle/jekyll-cv-crafter) template:
content lives in [`_data/cv.yml`](_data/cv.yml), rendering in
[`index.html`](index.html), styling in [`assets/cv.scss`](assets/cv.scss).

## Editing content

All resume content (summary, career history, skills, certifications,
education, languages, interests) is data-driven from `_data/cv.yml`. Update
that file only — `index.html` renders it automatically.

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## License

MIT — see [LICENSE](LICENSE).
