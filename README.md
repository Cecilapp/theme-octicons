# Octicons component theme

The Octicons component theme provides a Twig macro to use [Primer Octicons icons](https://primer.style/octicons/) in Cecil templates.

## Prerequisites

- A [Cecil](https://cecil.app) website

## Installation

```bash
composer require cecil/theme-octicons
```

> Or [download the latest archive](https://github.com/Cecilapp/theme-octicons/releases/latest/) and uncompress its content in `themes/octicons`.

## Usage

```twig
{% import 'macros/octicons.twig' as octicons %}

{{ octicons.svg('<icon>', <16|24>, '<class>') }}
```

- `size` is optional (default: `24`)
- `class` is optional
- If the icon isn't available in the requested size, the `question` icon is rendered instead (size `16`).

## Development

Install dependencies, then copy the Octicons data file (from `@primer/octicons`) to the `data` folder:

```bash
npm install
npm run build
```

### Demo

The `demo/` folder contains a website listing all the icons, using the theme under development:

```bash
php demo/link.php
cecil serve demo
```
