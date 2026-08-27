## Module 3: Text  Formatting

[⬅️Back to Index](./readme.md)
---
**Headings**

HTML has six levels of headings, `<h1>` through `<h6>`, from most to least important.

* `<h1>`: Main title of the page (largest/most important)
* `<h2>`: Major section
* `<h3>`: Subsection
* `<h4>`: Smaller subsection
* `<h5>`: Minor heading
* `<h6>`: Smallest heading

*Golden rule reminder:* use only one `<h1>` per page, and don't skip levels just for a bigger/smaller look — use CSS for that instead.
---
**Paragraphs & Line Breaks**

*Html*
``|
<p>This is a paragraph of text.</p>
<br> <!-- forces a single line break, no closing tag -->
<hr> <!-- draws a horizontal rule/divider line -->
```
---
**Basic Text Styling**

1. **Bold Text (`<b>`)**: Makes text bold for visual appearance.
   * Example: `<p>I am learning <b>HTML</b>.</p>`

2. **Strong Text (`<strong>`)**: Makes text bold and indicates that the text is important.
   * Example: `<p><strong>Warning!</strong> Save your work.</p>`

3. **Italic Text (`<i>`)**: Makes text italicized (often used for style/calligraphy).
   * Example: `<p>I love <i>music</i>.</p>`

4. **Emphasized Text (`<em>`)**: Adds emphasis by stressing a word (usually displayed in italics).
   * Example: `<p>Please <em>read carefully</em>.</p>`

5. **Underline (`<u>`)**: Used to underline text (unarticulated annotation).
   * Example: `<p><u>Welcome to HTML</u></p>`

6. **Highlight (`<mark>`)**: Highlights text in yellow.
   * Example: `<p>HTML is <mark>easy to learn</mark>.</p>`

7. **Small Text (`<small>`)**: Makes the text smaller.
   * Example: `<p>Hi, <small>people</small>.</p>`

8. **Subscript (`<sub>`)**: Lowers text, commonly used in chemical formulas.
   * Example: `<p>H<sub>2</sub>O</p>` $\rightarrow$ H₂O

9. **Superscript (`<sup>`)**: Raises text, commonly used in powers and exponents.
    * Example: `<p>2<sup>3</sup> = 8</p>` $\rightarrow$ 2³ = 8

10. **Deleted Text (`<del>`)**: Shows text that has been struck through/deleted.
    * Example: `<p>The price is <del>₹500</del> ₹350.</p>`

11. **Inserted Text (`<ins>`)**: Shows inserted text and automatically underlines it.
    * Example: `<p>I am learning <ins>HTML</ins>.</p>`
---