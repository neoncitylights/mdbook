# 📖 Markdown Template

[![CI](https://github.com/neoncitylights/mdbook-template/actions/workflows/ci.yml/badge.svg)](https://github.com/neoncitylights/mdbook-template/actions/workflows/ci.yml)
[![GitHub deployments](https://img.shields.io/github/deployments/neoncitylights/mdbook-template/github-pages?label=docs)](https://neoncitylights.github.io/mdbook-template/)

A repository template that builds a static documentation site using Markdown and mdBook.

Make a change, commit, push, and see the updates live on your GitHub Pages site!

## Features

- [x] *Linting markdown files* with [`markdownlint`](https://github.com/DavidAnson/markdownlint) and [`markdownlint-cli`](https://github.com/igorshubovych/markdownlint-cli)
- [x] *Auto-generated documentation* using [mdBook](https://github.com/rust-lang/mdBook) and [GitHub Pages](https://docs.github.com/en/pages)
- [x] *Continuous deployment* with [GitHub Actions](https://github.com/features/actions), with fast-build & deploy times (< 30 seconds)
- [x] *Dependency updates* with [Renovate](https://github.com/marketplace/renovate)
- [x] *Remote development* with [GitHub Codespaces](https://github.com/features/codespaces)

## Configure

- Configure mdBook: [`book.toml`](./book.toml) and [`SUMMARY.md`](./src/SUMMARY.md) ([official docs](https://rust-lang.github.io/mdBook/format/configuration/index.html))
- Configure markdownlint: [`.markdownlint.json`](./.markdownlint.json) ([official docs](https://github.com/DavidAnson/markdownlint#optionsconfig), [example config file](https://github.com/DavidAnson/markdownlint/blob/main/schema/.markdownlint.jsonc))

## Build locally

```bash
git clone https://github.com/neoncitylights/mdbook-template.git
cd mdbook-template
npm install
npm run build
```

## Lint markdown files

- To lint markdown: `npm run lint`
- To auto-fix lint errors: `npm run lint:fix`
