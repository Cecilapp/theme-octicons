# Octicons component theme

The Octicons component theme provides a Twig macro to use [Primer Octicons icons](https://primer.style/octicons/) in Cecil templates.

```twig
{% import 'macros/octicons.twig' as octicons %}

{{ octicons.svg('<icon>', <16|24>, '<class>') }}
```
