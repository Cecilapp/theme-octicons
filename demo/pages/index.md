---
title: Home
gallery: true
---
# Octicons for Cecil

This website is the demo of the [_Octicons_ component theme](https://github.com/Cecilapp/theme-octicons) for [Cecil](https://cecil.app): a Twig macro to render [Primer Octicons](https://primer.style/octicons/) as inline SVG.

```twig
{% import 'macros/octicons.twig' as octicons %}

{{ octicons.svg('mark-github', 24, 'icon') }}
```

- `size` is optional: `12`, `16` or `24` (some icons also exist in `48` and `96`), default: `24`;
- `class` is optional;
- if the icon isn't available in the requested size, the `question` icon is rendered instead.

Icons use `currentColor`, so they follow the text color. Search an icon below, then click it to copy its macro call.
