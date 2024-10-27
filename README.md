# `halve-z`
[![Netlify Status](https://api.netlify.com/api/v1/badges/352a12ed-cdba-4545-9256-9fb698f5a94f/deploy-status?branch=trunk)](https://app.netlify.com/sites/halve-z/deploys)

A two-column theme for **Zola**.

![logo](https://raw.githubusercontent.com/charlesrocket/halve-z/trunk/static/favicon-32x32.png)

## Features

This is a _retro_ port of [Halve](https://github.com/TaylanTatli/Halve) (**Jekyll**). It features:

* search
* taxonomies
* PWA (dynamic cache/offline mode)
* notifications
* auto color schemes
* ToC
* pagination
* media shortcodes
* SEO
* CSP
* project cards
* comments ([Cactus](https://gitlab.com/cactus-comments/)/[Giscus](https://github.com/giscus/giscus))
* read time

## Installation

Add theme submodule using `git`:

```sh
git submodule add https://github.com/charlesrocket/halve-z themes/halve-z
```

### Updates

Use the following command to update theme to the latest version:

```
git submodule update --recursive --remote
```

## Configuration

1. Copy theme's [config.toml](https://github.com/charlesrocket/halve-z/blob/trunk/config.toml) into your project's root directory. Set variables as required and add `theme = "halve-z"` at the **top** of the config file.
2. Copy the content to get started:

```
cp -R -f themes/halve-z/content/ content/
```

## Usage

See demo [posts](https://halve-z.netlify.app/posts/).
