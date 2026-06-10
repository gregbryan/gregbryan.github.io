# gregbryan.github.io

Personal academic website of Greg Bryan — Professor of Astronomy, Columbia University, and Director of the Simons Collaboration on [Learning the Universe](https://learning-the-universe.org/).

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme. Deployed to GitHub Pages by `.github/workflows/deploy.yml` on every push to `main`.

## Local development

```bash
export PATH="/usr/local/opt/ruby/bin:$PATH"   # Homebrew Ruby (>= 3.x required)
export LC_ALL=en_US.UTF-8
bundle install
bundle exec jekyll serve
```

## Updating publications

`_bibliography/papers.bib` is generated from NASA/ADS (author query `"Bryan, Greg L."`, refereed + recent arXiv preprints), with `bibtex_show`, `arxiv`, `abbr`, and `html` (ADS link) fields added per entry and the top-cited papers marked `selected={true}`.
