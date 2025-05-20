# DATA 8 Summer 2025 Website

[![Run all page tests](https://github.com/data-8/su25/actions/workflows/rspec.yml/badge.svg)](https://github.com/data-8/su25/actions/workflows/rspec.yml)

## Installation

Prerequisites:

- You have everything that [Jekyll requires](https://jekyllrb.com/docs/installation/)
- You have installed [Bundler](https://bundler.io/): `gem install jekyll bundler`

After cloning this repository and navigating into the directory, run the following command to install dependencies
```
cd YOUR_REPO
bundle install
```

## Usage

To run the site locally, run:

```
bundle exec jekyll serve
```

## Deployment

This site is deployed via a [GitHub Action Workflow](.github/workflows/jekyll.yml). For more information see [GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

## License

[MIT](LICENSE)
