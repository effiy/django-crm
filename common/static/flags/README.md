---
title: Country Flags
tags: [flags, svg, flag-icons, internationalization, assets]
category: assets
created: 2024
updated: 2026-10-20
source: external
type: index
status: stable
lifecycle: active
---

# Country Flags

---

## 💡 概述

The SVG flags in this directory come from [flag-icons](https://github.com/lipis/flag-icons).
This project includes both image sets:

- `4x3/` — flags with a 4:3 aspect ratio;
- `1x1/` — square flags.

---

## ⚡ 功能

- 4:3 aspect ratio flag set (`4x3/`)
- 1:1 square flag set (`1x1/`)
- CSS-based flag display via `common/static/css/flag-icons.css`
- Django Admin integration
- Country identification via ISO 3166-1 alpha-2 codes

---

## 📊 指标

「待补充」

---

## 🏛️ 设计

The styles are in `common/static/css/flag-icons.css` and reference the SVG files
using paths relative to the stylesheet. Django Admin loads this stylesheet.

---

## 📁 目录

- `4x3/` — 4:3 aspect ratio flags
- `1x1/` — 1:1 square flags

---

## 🔗 资源

- [flag-icons](https://github.com/lipis/flag-icons) — upstream project (MIT License)
- [MIT License](https://github.com/lipis/flag-icons/blob/main/LICENSE)

---

## 🚀 快速开始

For example, the Ukrainian flag can be displayed as:

```html
<span class="fi fi-ua"></span>
```

The class after `fi-` is the country's lowercase, two-letter ISO 3166-1 alpha-2
code. Add the `fis` class to use the square version:

```html
<span class="fi fi-ua fis"></span>
```

When updating the assets, keep the CSS and SVG files in sync and preserve the
`../flags/4x3/` and `../flags/1x1/` paths.

---

## ⚙️ 技术栈

- SVG flag assets
- CSS flag-icons stylesheet
- Django Admin integration

---

Many thanks to the `flag-icons` maintainers and contributors for creating and
maintaining this useful open-source project.