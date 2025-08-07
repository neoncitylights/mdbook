# Markdown template
[![CI](https://img.shields.io/github/actions/workflow/status/neoncitylights/mdbook/.github/workflows/ci.yml?style=flat-square)](https://github.com/neoncitylights/mdbook/actions/workflows/ci.yml)
[![GitHub deployments](https://img.shields.io/github/deployments/neoncitylights/mdbook/github-pages?label=docs&style=flat-square)](https://neoncitylights.github.io/mdbook/)

A repository template that builds a static documentation site using Markdown and mdBook.

## Features
- [x] Auto-generated documentation using [mdBook](https://github.com/rust-lang/mdBook) and [GitHub Pages](https://docs.github.com/en/pages)
- [x] Continuous deployment with [GitHub Actions](https://github.com/features/actions)
- [x] Dependency updates with [Dependabot](https://github.com/dependabot)

## Configure
| Tool              | File                                                     | Documentation                                                              |
| ----------------- | -------------------------------------------------------- | -------------------------------------------------------------------------- |
| mdBook            | [`book.toml`](./book.toml)                               | [docs](https://rust-lang.github.io/mdBook/format/configuration/index.html) |
| mdBook            | [`SUMMARY.md`](./src/SUMMARY.md)                         | [docs](https://rust-lang.github.io/mdBook/format/summary.html)             |

## Build locally
- With Docker: `docker compose build` + `docker compose up`
- Without Docker: `mdbook build` + `mdbook serve`

### System requirements
- [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html) (Rust package manager)
- [mdBook](https://rust-lang.github.io/mdBook/guide/installation.html) (Static site generator with Markdown)
