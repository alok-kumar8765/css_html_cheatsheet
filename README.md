
# 🚀 **The Ultimate Web Dev Cheat Sheet: HTML + CSS Grid**

A combined, high-quality reference sheet covering essential **HTML5 tags** and the full **CSS Grid layout system**.
Designed for developers who want a fast, structured, and practical lookup resource.

---

## 🛡️ Badges

<p align="left">
  <img src="https://img.shields.io/github/stars/alok-kumar8765/css_html_cheatsheet?style=flat&color=yellow" alt="stars"/>
  <img src="https://img.shields.io/github/forks/alok-kumar8765/css_html_cheatsheet?style=flat&color=orange" alt="forks"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen" alt="prs welcome"/>
  <img src="https://img.shields.io/badge/Contributions-Open-blue" alt="contributions"/>
  <img src="https://img.shields.io/badge/Code%20Quality-Excellent-success" alt="code quality"/>
  <img src="https://img.shields.io/badge/License-MIT-purple" alt="license"/>
</p>


---

# 📑 Table of Contents

* [🚀 The Ultimate Web Dev Cheat Sheet](#-the-ultimate-web-dev-cheat-sheet-html--css-grid)
* [🛡️ Badges](#️-badges)
* [📘 HTML Tags Cheat Sheet](#-html-tags-cheat-sheet)
* [🎨 CSS Grid Cheat Sheet](#-css-grid-cheat-sheet)

  * [Grid Container Properties](#1-grid-container-properties)
  * [Grid Item Properties](#2-grid-item-properties)
* [🤝 Contribution & Discussion](#-contribution--discussion)

---

# 📘 **HTML Tags Cheat Sheet**

Quick reference for essential HTML5 tags, their purpose, and example usage.

| S/N | Tag               | Description                 | Example                      |
| :-: | ----------------- | --------------------------- | ---------------------------- |
|  1  | `<!DOCTYPE html>` | Defines HTML5 document type | `<!DOCTYPE html>`            |
|  2  | `<html>`          | Root element                | `<html lang="en"></html>`    |
|  3  | `<head>`          | Metadata container          | `<head>...</head>`           |
|  4  | `<body>`          | Document body content       | `<body>...</body>`           |
|  5  | `<h1>`–`<h6>`     | Headings                    | `<h1>Title</h1>`             |
|  6  | `<p>`             | Paragraph text              | `<p>Hello</p>`               |
|  7  | `<br>`            | Line break                  | `Hello<br>World`             |
|  8  | `<strong>`        | Important (bold) text       | `<strong>Warning</strong>`   |
|  9  | `<em>`            | Emphasized (italic)         | `<em>Note</em>`              |
|  10 | `<mark>`          | Highlighted text            | `<mark>Yellow</mark>`        |
|  11 | `<a>`             | Hyperlink                   | `<a href="#">Click</a>`      |
|  12 | `<img>`           | Image                       | `<img src="x.jpg">`          |
|  13 | `<ul>`            | Bullet list                 | `<ul><li>Item</li></ul>`     |
|  14 | `<ol>`            | Numbered list               | `<ol><li>One</li></ol>`      |
|  15 | `<table>`         | Table container             | `<table>...</table>`         |
|  16 | `<form>`          | Form wrapper                | `<form>...</form>`           |
|  17 | `<input>`         | Form input                  | `<input type="text">`        |
|  18 | `<textarea>`      | Multiline text input        | `<textarea></textarea>`      |
|  19 | `<select>`        | Dropdown menu               | `<select>...</select>`       |
|  20 | `<label>`         | Form label                  | `<label for="">Name</label>` |
|  21 | `<header>`        | Header section              | `<header>...</header>`       |
|  22 | `<footer>`        | Footer section              | `<footer>...</footer>`       |
|  23 | `<section>`       | Content section             | `<section>...</section>`     |
|  24 | `<article>`       | Independent article         | `<article>...</article>`     |
|  25 | `<nav>`           | Navigation bar              | `<nav>...</nav>`             |
|  26 | `<aside>`         | Sidebar content             | `<aside>...</aside>`         |
|  27 | `<figure>`        | Media with caption          | `<figure>...</figure>`       |
|  28 | `<details>`       | Expand/collapse panel       | `<details>...</details>`     |
|  29 | `<dialog>`        | Popup dialog                | `<dialog open></dialog>`     |

---

# 🎨 **CSS Grid Cheat Sheet**

CSS Grid provides advanced two-dimensional layout control.

---

## **1. Grid Container Properties**

| S/N | Property                | Description                         | Example                  | Tricks                 |
| :-: | ----------------------- | ----------------------------------- | ------------------------ | ---------------------- |
|  1  | `display: grid`         | Turns element into a grid container | `display: grid;`         | `inline-grid`          |
|  2  | `grid-template-columns` | Define column sizes                 | `12px 12px 12px;`        | `repeat(3, 12px)`      |
|  3  | `grid-template-rows`    | Define row sizes                    | `12px 12px 12px;`        | `repeat(3, auto)`      |
|  4  | `align-items`           | Vertical alignment                  | `align-items: start;`    | `center`, `stretch`    |
|  5  | `justify-items`         | Horizontal alignment                | `justify-items: center;` | `start`, `stretch`     |
|  6  | `justify-content`       | Align entire grid horizontally      | `space-between`          | `space-evenly`         |
|  7  | `grid-row-gap`          | Row gap                             | `grid-row-gap: 1px;`     | Use `gap` instead      |
|  8  | `grid-column-gap`       | Column gap                          | `grid-column-gap: 9px;`  | Use `gap` instead      |
|  9  | `grid-gap`              | Row + column gap shorthand          | `grid-gap: 6px;`         | Now replaced by `gap:` |

---

## **2. Grid Item Properties**

| S/N | Property            | Description       | Example                | Tricks           |
| :-: | ------------------- | ----------------- | ---------------------- | ---------------- |
|  1  | `grid-column-start` | Start column line | `grid-column-start: 1` | Use shorthand    |
|  2  | `grid-column-end`   | End column line   | `grid-column-end: 3`   | `span 3`         |
|  3  | `grid-column`       | Column shorthand  | `2 / 3`                | `2 / span 2`     |
|  4  | `grid-row-start`    | Start row line    | `grid-row-start: 1`    | Combine          |
|  5  | `grid-row-end`      | End row line      | `grid-row-end: 3`      | `span 3`         |
|  6  | `grid-row`          | Row shorthand     | `1 / 3`                | `1 / span 3`     |
|  7  | Combined            | Span row + column | `grid-row: 1 / span 2` | Create 2×2 items |

---

## **3. Sample Images**

| S/N | Image            | 
| :-: | ------------------- |
|  1  | <img src="https://github.com/alok-kumar8765/css_html_cheatsheet/blob/main/css.jpg" height="50%" width="50%"> | 
|  2  | <img src="https://github.com/alok-kumar8765/css_html_cheatsheet/blob/main/css1.jpg" height="50%" width="50%">   | 
|  3  | <img src="https://github.com/alok-kumar8765/css_html_cheatsheet/blob/main/css2.jpg" height="50%" width="50%">   | 
|  4  | <img src="https://github.com/alok-kumar8765/css_html_cheatsheet/blob/main/css3.jpg" height="50%" width="50%">   | 
|  5  | <img src="https://github.com/alok-kumar8765/css_html_cheatsheet/blob/main/css4.jpg" height="50%" width="50%">   | 
|  6  | <img src="https://github.com/alok-kumar8765/css_html_cheatsheet/blob/main/css5.jpg" height="50%" width="50%">   | 
|  7  | <img src="https://github.com/alok-kumar8765/css_html_cheatsheet/blob/main/html.jpg" height="50%" width="50%">   | 

---

# 🤝 **Contribution & Discussion**

### 💬 Contribute

* Add HTML/CSS tips
* Improve examples
* Submit fixes or enhancements
* Challenge assumptions for better clarity

### 🧠 Discussion Starters

✔ Prefer **CSS Grid or Flexbox** for page layout?
✔ Common gotchas with `grid-template-areas`?
✔ Should we replace `grid-gap` entirely with modern `gap`? (Yes — modern standard)

---

# ⭐ Support the Project

If this cheat sheet helps you, please give the repo a **star ⭐** to support future improvements!

---
