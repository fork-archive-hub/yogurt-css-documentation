---
id: line-height
title: Line Height
description: Utilities for sets the line height.
layout: default
---

> Typography

# Line Height

Utilities for sets the line height.

---

## Class

| <span class="px-3 py-1 text-white (dark)text-charcoal-100 bg-charcoal-100 (dark)bg-gray-600 rounded-full">class</span> | <span class="px-3 py-1 text-white (dark)text-charcoal-100 bg-charcoal-100 (dark)bg-gray-600 rounded-full">css</span> |
|:--|:--|
| depth-none | line-height: 1 |
| depth-tight | line-height: 1.25 |
| depth-snug | line-height: 1.375 |
| depth-normal | line-height: 1.5 |
| depth-relaxed | line-height: 1.625 |
| depth-loose | line-height: 2 |
| depth-3 | line-height: .75rem |
| depth-4 | line-height: 1rem |
| depth-5 | line-height: 1.25rem |
| depth-6 | line-height: 1.5rem |
| depth-7 | line-height: 1.75rem |
| depth-8 | line-height: 2rem |
| depth-9 | line-height: 2.25rem |
| depth-10 | line-height: 2.5rem |

---

## Usage

<y class="my-2 mx-auto max-w-md">
  <y class="flex">
    <y class="depth-tight mx-2 p-4 bg-gray-300">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    </y>
    <y class="depth-loose mx-2 p-4 bg-gray-300">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    </y>
  </y>
</y>

```html
<!-- Example -->
<y class="depth-tight">
  ...
  ...
  ...
</y>
```

---

## Customize <a class="ml-1 px-2 py-1 text-sm text-gray-600 (dark)text-charcoal-100 bg-gray-300 (dark)bg-gray-600" href="/plugin-api/">More</a>

```scss
// @file: `src/_plugins.scss`
@include plugin(
  (
    utility: 'depth',
    //variant: 'responsive',
    property: 'line-height',
    modifier: (
      'super': '3rem',
      'ultra': '4rem'
      ...
    )
  )
)
```

---

## Variant

| <span class="font-semibold underline">Variant</span> | <span class="font-semibold underline">Enabled</span> | <span class="font-semibold underline">Responsive</span> |
|:-:|:-:|:-:|
| Default | Yes | Yes |
| Dark Theme | | |
| hover| | |
| group-hover | | |
| focus | | |
| focus-within | | |
| active | | |
| visited | | |
| checked | | |
| disabled | | |