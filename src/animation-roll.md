---
id: animation-roll
title: Roll Animation
description: Utilities for sets the rolling animation to an element.
layout: default
---

> Animations

# Rolling <span class="ml-1 px-2 py-1 text-sm text-gray-600 (dark)text-charcoal-100 bg-gray-300 (dark)bg-gray-600">v1.0.9</span>

Utilities for sets the rolling animation to an element.

---

## Class

| <span class="px-3 py-1 text-white (dark)text-charcoal-100 bg-charcoal-100 (dark)bg-gray-600 rounded-full">class</span> | <span class="px-3 py-1 text-white (dark)text-charcoal-100 bg-charcoal-100 (dark)bg-gray-600 rounded-full">css</span> | |
|:--|:--|:-:|
| roll-in-left | @keyframes roll-in-left { from { opacity: 0; transform: translate3d(-100%, 0, 0) } to { opacity: 1; transform: translate3d(0, 0, 0) }} | <y class="text-lg animation roll-in-left duration-800 delay-2 loop-infinite">Text</y> |
| roll-in-right | @keyframes roll-in-right { from { opacity: 0; transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg) } to { opacity: 1; transform: translate3d(0, 0, 0); }} | <y class="text-lg animation roll-in-right duration-800 delay-2 loop-infinite">Text</y> |
| roll-out-left | @keyframes roll-out-left { from { opacity: 1 } to { opacity: 0; transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg) }} | <y class="text-lg animation roll-out-left duration-800 delay-2 loop-infinite">Text</y> |
| roll-out-right | @keyframes roll-out-right { from { opacity: 1 } to { opacity: 0; transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg) }} | <y class="text-lg animation roll-out-right duration-800 delay-2 loop-infinite">Text</y> |

<y class="m-4 p-3 border-l-8 border-gray-600 text-sm text-gray-600 bg-gray-200 (dark)bg-gray-800">
  <span class="pr-1 font-semibold">
    Note:
  </span>
  Utility customizing is unavailable.
</y>

---

## Usage

Set basic roll animation.

```html
<!-- Example -->
<y class="animation roll-in-left">
  ...
</y>
```

Mix with duration.

```html
<!-- Example -->
<y class="animation roll-in-left duration-2000">
  ...
</y>
```

Mix with duration and delay.

```html
<!-- Example -->
<y class="animation roll-in-left duration-2000 delay-2">
  ...
</y>
```

Mix with duration, delay and infinite looping.

```html
<!-- Example -->
<y class="animation roll-in-left duration-2000 delay-2 infinite">
  ...
</y>
```

---

## Variant

| <span class="font-semibold underline">Variant</span> | <span class="font-semibold underline">Enabled</span> | <span class="font-semibold underline">Responsive</span> |
|:-:|:-:|:-:|
| Default | Yes | |
| Dark Theme | | |
| hover | Yes | |
| group-hover | | |
| focus | | |
| focus-within | | |
| active | | |
| visited | | |
| checked | | |
| disabled | | |