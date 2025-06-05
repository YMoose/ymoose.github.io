# jekyll-theme-read-the-docs

![visitors](https://visitor-badge.laobi.icu/badge?page_id=ymoose.blog)
[![CodeQL Advanced](https://github.com/YMoose/ymoose.github.io/actions/workflows/codeql.yml/badge.svg?branch=dev)](https://github.com/YMoose/ymoose.github.io/actions/workflows/codeql.yml)
[![Umami - GDPR compliant alternative to Google Analytics](https://img.shields.io/badge/analytics-umami-green)](https://analytics.umami.is/share/ "Umami - GDPR compliant alternative to Google Analytics")
[![License EUPL 1.2](https://img.shields.io/badge/License-EUPL--1.2-blue.svg)](LICENSE)
[![Follow Moose on GitHub](https://img.shields.io/github/followers/YMoose?label=YMoose&style=social)](https://github.com/YMoose "Follow Moose on GitHub")

> Read the Docs 📖 like Jekyll Theme for GitHub Pages

## What it does?

This theme is inspired by [sphinx-rtd-theme](https://github.com/jekyll-theme-read-the-docs/sphinx_rtd_theme) and refactored with:

- [@primer/css](https://github.com/primer/css)
- [github-pages](https://github.com/github/pages-gem) ([dependency versions](https://pages.github.com/versions/))

## Quick start

```yml
remote_theme: https://github.com/JV-conseil/jekyll-theme-read-the-docs
```

You can [generate][rundocs/starter] with the same files and folders from [rundocs/starter][rundocs/starter]

## Usage

Documentation that can guide how to create with Github pages, please refer to [rundocs/jekyll-rtd-theme](https://github.com/rundocs/jekyll-rtd-theme) for details

## Features

- Shortcodes (Toasts card, mermaid)
- Pages Plugins (emoji, gist, avatar, mentions)
- Auto generate sidebar
- [Attribute List Definitions](https://kramdown.gettalong.org/syntax.html#attribute-list-definitions) (Primer/css utilities, Font Awesome 4)
- Service worker (caches)
- SEO (404, robots.txt, sitemap.xml)
- Canonical Link (Open Graph, Twitter Card, Schema data)

## Options

| name          | default value        | description       |
| ------------- | -------------------- | ----------------- |
| `title`       | repo name            |                   |
| `description` | repo description     |                   |
| `url`         | user domain or cname |                   |
| `baseurl`     | repo name            |                   |
| `lang`        | `en`                 |                   |
| `direction`   | `auto`               | `ltr` or `rtl`    |
| `highlighter` | `rouge`              | Cannot be changed |

```yml
# folders sort
readme_index:
  with_frontmatter: true

meta:
  key1: value1
  key2: value2
  .
  .
  .

google:
  gtag:
  adsense:
  site_verification:

# GDPR compliant alternative to Google Analytics
mouseflow:
  project_api_key:

posthog:
  project_api_key:

telemetry:
  app_id:
  user_identifier:

umami:
  website_id:

mathjax: # this will prased to json, default: {}

# NOTE: mermaid custom link are no longer supported
# instead mermaid is updated to the lastest version
# available through cdn.jsdelivr.net
# mermaid:
#   custom:     # mermaid link
#   initialize: # this will prased to json, default: {}

scss:   # also _includes/extra/styles.scss
script: # also _includes/extra/script.js

translate:
  # shortcodes
  danger:
  note:
  tip:
  warning:
  # 404
  not_found:
  # copyright
  revision:
  # search
  searching:
  search:
  search_docs:
  search_results:
  search_results_found: # the "#" in this translate will replaced with results size!
  search_results_not_found:

plugins:
  - jemoji
  - jekyll-avatar
  - jekyll-mentions
```

## Sponsorship

If this project helps you, you can offer me a cup of coffee ☕️ :-)

[![Become a sponsor to JV-conseil](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/JV-conseil)

<!-- links -->

[rundocs/starter]: https://github.com/rundocs/starter
