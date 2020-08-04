---
id: theme-invert
title: Theme Invert
description: Utilities for sets page theme either dark or light by applying force invert.
layout: default
---

> Theme

## Theme Invert <span class="ml-1 px-2 py-1 text-sm text-gray-600 bg-gray-300">v1.0.9</span>

Utilities for sets page theme either dark or light by applying force invert.

### Class

| <span class="px-3 py-1 text-white bg-charcoal-100 rounded-full">attribute</span> | <span class="px-3 py-1 text-white bg-charcoal-100 rounded-full">css</span> |
|:--|:--|
| theme="invert" | html[theme="invert"], img[theme="invert"], [theme="invert"] { filter: invert(1) hue-rotate(180deg); |

<y class="mt-4 p-3 border-l-8 border-gray-600 text-sm text-gray-600 bg-gray-200">
  <span class="pr-1 font-semibold">
    Note:
  </span>
  Utility customizing is unavailable.
</y>

<y class="mt-2 p-3 border-l-8 border-orange-600 text-sm text-orange-600 bg-orange-200">
  <span class="pr-1 font-semibold">
    Note:
  </span>
  Auto theme not supported. Affected to all devices (desktop, mobile).
</y>

### Usage

The basic set up for `theme="invert"` attribute is at the `<html>` tag. This allows `theme="invert"` to attenuate colors of the page theme but not changing any color of the application.

```html
<html theme="invert">
  ...
</html>
```

But, the images and some other elements will be look inverted. To compensate that, apply the same `theme="invert"` attribute to all affected elments, like in the example.

```html
<html theme="invert">
  ...
    <!-- e.g. To compensate inverted image -->
    <img theme="invert">
    <!-- e.g. To compensate any inverted elements -->
    <y theme="invert"></y>
    <span theme="invert"></span>
  ...
</html>
```

### Variant

| <span class="font-semibold underline">Variant</span> | <span class="font-semibold underline">Enabled</span> | <span class="font-semibold underline">Responsive</span> |
|:-:|:-:|:-:|
| Default | Yes | |
| hover| | |
| group-hover | | |
| focus | | |
| active | | |
| visited | | |
| disabled | | |