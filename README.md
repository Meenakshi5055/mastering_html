# mastering_html

### An organized, step-by-step HTML learning resource — from core basics to advanced mastery. Built module by module, with older/legacy tags kept for reference and clearly flagged where a modern approach (CSS/JS) has replaced them.

## 📜 Golden Rules:

**Follow these no matter what you're writing:**

* Always start with `<!DOCTYPE html>`. It must be the very first line of every page.
* Always close your tags. Every opening tag needs a matching closing tag, unless it's self-closing (`<br>`, `<img>`, `<input>`, `<meta>`, `<hr>`).
* Nest tags properly. If you open tag A then tag B, close B before you close A. Never let tags overlap.
* Use lowercase for tag names and attributes. `<div>` not `<DIV>` — it's the widely followed convention and improves consistency.
* Always quote attribute values. class="box" not class=box.
* Indent nested elements consistently. It makes your structure readable at a glance.
* Use semantic tags over generic `<div>`s whenever a tag exists that describes what the content actually is (`<nav>`, `<article>`, `<footer>`, etc.). See Module 9.
* Every `<img>` needs an alt attribute. It's essential for accessibility and for when images fail to load.
* Only one `<h1>` per page. Use headings in order (don't skip from `<h2>` to `<h5>` for a size effect — that's what CSS is for).
* Keep structure (HTML), style (CSS), and behavior (JS) separate. Avoid inline style="" and inline onclick="" where possible — link external files instead.
* Always include `<meta charset="UTF-8">` and the viewport meta tag. See Module 10.
* Pair every form input with a `<label>`. Accessibility matters, not just appearance.
* When you use a legacy/outdated tag, know it and say so. This repo keeps them for reference (marked ⚠️ Outdated) — don't use them in new projects unless you have a specific reason to.


# 📚 Module Index

1. [Introduction to HTML](#introduction-to-html)
2. [Document Structure](#document-structure)
3. [Text & Formatting](#text--formatting)
4. [Lists](#lists)
5. [Links](#links)
6. [Images & Multimedia](#images--multimedia)
7. [Tables](#tables)
8. [Forms](#forms)
9. [Semantic HTML & Layout](#semantic-html--layout)
10. [Meta Tags & SEO Basics](#meta-tags--seo-basics)
11. [Iframes & Frames](#iframes--frames)
12. [HTML + CSS & JavaScript](#html--css--javascript)
13. [HTML Tag Reference](#html-tag-reference)
