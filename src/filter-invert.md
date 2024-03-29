---
id: filter-invert
title: Filter Invert
description: Utilities for sets filter invert effect to an element.
layout: default
---

> Filters

# Invert

Utilities for sets filter inverts effect to an element.

---

## Class

| <span class="px-3 py-1 text-white (dark)text-charcoal-100 bg-charcoal-100 (dark)bg-gray-600 rounded-full">class</span> | <span class="px-3 py-1 text-white (dark)text-charcoal-100 bg-charcoal-100 (dark)bg-gray-600 rounded-full">css</span> |
|:--|:--|
| invert-0 | filter: invert(0) |
| invert-1 | filter: invert(1.0) |

---

## Usage

<y class="mx-2 my-2 mx-auto flex">
  <y class="p-2 max-w-sm">
    <img class="w-full h-48 object-cover object-center overflow-hidden rounded-lg shadow"
         src="https://picsum.photos/500?=5">
    <y class="pt-2 text-sm text-center">
      Filter: OFF
    </y>
  </y>
  <y class="m-2 max-w-sm">
    <img class="invert-1 w-full h-48 object-cover object-center overflow-hidden rounded-lg"
         src="https://picsum.photos/500?=5">
    <y class="pt-2 text-sm text-center">
      Filter: ON
    </y>
  </y>
</y>

```html
<!-- Example -->
<img class="invert-1 ..."
     src="...">

<y class="invert-1 ..."
   style="background-image:url(...)"></y>
```

<span class="ml-1 px-2 py-1 text-sm text-gray-600 (dark)text-charcoal-100 bg-gray-300 (dark)bg-gray-600">v1.1.1</span> Set auto dark theme enabled to an element with added `(dark)` prefix.

```html
<!-- Example -->
<img class="invert-1 (dark)invert-0 ..."
     src="...">

<y class="invert-1 (dark)invert-0 ..."
   style="background-image:url(...)"></y>
```

---

## Variant

| <span class="font-semibold underline">Variant</span> | <span class="font-semibold underline">Enabled</span> | <span class="font-semibold underline">Responsive</span> |
|:-:|:-:|:-:|
| Default | Yes | |
| Dark Theme | | |
| hover| | |
| group-hover | | |
| focus | | |
| focus-within | | |
| active | | |
| visited | | |
| checked | | |
| disabled | | |