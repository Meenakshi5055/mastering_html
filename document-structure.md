## Module 2: Document Structure

**Every HTML page follows the same basic skeleton. These are the foundational tags required to build any standard webpage.**


[⬅️Back to Index](./readme.md)
---

**The Basic Skeleton**

*Html code*
```
<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
```
**Breaking It Down**

* `<!DOCTYPE html>`
Tells the browser this is an HTML5 document. It's not a tag exactly — it's a declaration, and it must be the very first line of the file.
* `<html>...</html>`
The root element. It wraps all content on the page — everything else goes inside it.
* `<head>...</head>`
Contains invisible metadata — information about the page rather than content shown to the user. This includes the title, links to CSS files, character encoding, and SEO meta tags (covered in Module 10).
* `<body>...</body>`
Contains all the visible content — text, images, links, forms, everything the user actually sees and interacts with.

**Tags vs. Elements vs. Attributes**

It's easy to mix these words up, so here's the distinction:

| Term | Meaning| Example |
| --- | --- | --- |
| Tag | The markup itself, in angle brackets | <p>, </p> |
| Element | The tag(s) + the content together| <p>Hello</p> |
| Attribute | Extra info added inside the opening tag |

**Opening & Closing Tags**

Most tags come in pairs:

*Html code*

`<p>This is a paragraph.</p>`

- `<p>` — opening tag
- `</p>` — closing tag (note the /)
-Everything between them is the *content*
Some tags are self-closing (no content, no closing tag needed) — e.g. `<br>`, `<img>`, `<hr>`, `<meta>`, `<input>`.

**Nesting & Indentation**

Elements can contain other elements — this is called *nesting*. Always indent nested elements consistently; it makes your code far easier to read.

*Html code*
```
<body>
  <header>
    <h1>My Site</h1>
  </header>
  <main>
    <p>Some content here.</p>
  </main>
</body>
```
**Comments**

Use comments to leave notes in your code that the browser ignores, it helps the coder to understand what that line is actually about:

*Html code*
```
<!-- This is a comment, it won't show on the page -->
```
---
**Core Attributes**

Four attributes can be used on almost every HTML element — worth knowing early since you'll see them everywhere.

|Attribute|Purpose|
|---|---|
|id|Uniquely identifies one element on the page
|title|Suggested title — usually shown as a tooltip on hover|
|class|Associates the element with a CSS style/class (can hold multiple, space-separated)|
|style|Applies inline CSS rules directly to the element|

---
[⬅️ Previous module 01:Introduction to HTML](./introduction-to-html.md)|

[➡️ Next module 03:Text formatting](./text-formatting.md)