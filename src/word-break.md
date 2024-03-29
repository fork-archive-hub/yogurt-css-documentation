---
id: word-break
title: Word Break
description: Utilities for sets the word breaks of an element.
layout: default
---

> Typography

# Word Break

Utilities for sets the word breaks of an element.

---

## Class

| <span class="px-3 py-1 text-white (dark)text-charcoal-100 bg-charcoal-100 (dark)bg-gray-600 rounded-full">class</span> | <span class="px-3 py-1 text-white (dark)text-charcoal-100 bg-charcoal-100 (dark)bg-gray-600 rounded-full">css</span> |
|:--|:--|
| break-normal | word-break: normal; <br> overflow-wrap: normal |
| break-words | overflow-wrap: break-word; |
| break-all | word-break: break-all;
| truncate | overflow: hidden; <br> text-overflow: ellipsis; <br> white-space: nowrap |

---

## Usage

Set text paragraph break line normally.

<y class="my-2 mx-auto max-w-sm">
  <y class="p-4 bg-gray-300 break-normal">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis quidem itaque beatae, rem teneturuiaiureeumnatusenimmaximelaudantiumquibusdamillonihil, reprehenderit saepe quam aliquid odio accusamus.
  </y>
</y>

```html
<!-- Example -->
<y class="break-normal">
  ...
</y>
```

Set text paragraph break only words.

<y class="my-2 mx-auto max-w-sm">
  <y class="p-4 bg-gray-300 break-words">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis quidem itaque beatae, rem teneturuiaiureeumnatusenimmaximelaudantiumquibusdamillonihil, reprehenderit saepe quam aliquid odio accusamus.
  </y>
</y>

```html
<!-- Example -->
<y class="break-words">
  ...
</y>
```

Set text paragraph break all lines and words.

<y class="my-2 mx-auto max-w-sm">
  <y class="p-4 bg-gray-300 break-all">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis quidem itaque beatae, rem teneturuiaiureeumnatusenimmaximelaudantiumquibusdamillonihil, reprehenderit saepe quam aliquid odio accusamus.
  </y>
</y>

```html
<!-- Example -->
<y class="break-all">
  ...
</y>
```

Set text paragraph truncate into a single line.

<y class="my-2 mx-auto max-w-sm">
  <y class="p-4 bg-gray-300 truncate">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis quidem itaque beatae, rem teneturuiaiureeumnatusenimmaximelaudantiumquibusdamillonihil, reprehenderit saepe quam aliquid odio accusamus.
  </y>
</y>

```html
<!-- Example -->
<y class="truncate">
  ...
</y>
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