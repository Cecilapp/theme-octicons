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
