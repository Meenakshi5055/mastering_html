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

Golden rule reminder: use only one `<h1>` per page, and don't skip levels just for a bigger/smaller look — use CSS for that instead.

---
**Paragraphs & Line Breaks**

*Html*
```
<p>This is a paragraph of text.</p>
<br> <!-- forces a single line break, no closing tag. Helps you have the text in new line. -->
<hr> <!-- draws a horizontal rule/divider line in between. For not blending paragraphs or content together -->
```

*Example html code*
```
<h1>My profile</h1><br>
<p>Welcome to my webpage</p>
<hr>
<h2>My hobbies<h2>
<p>Listening to music and writing coding</p>
```
[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)
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

7. **Small Text (`<small>`)**: Makes the text smaller.HTML5 redefined its meaning: it's for side-comments/fine print/legal text, not just "smaller size" for its own sake.
   * Example: `<p>Hi, <small>people</small>.</p>`

8. **Subscript (`<sub>`)**: Lowers text, commonly used in chemical formulas.
   * Example: `<p>H<sub>2</sub>O</p>` $\rightarrow$ H₂O

9. **Superscript (`<sup>`)**: Raises text, commonly used in powers and exponents.
    * Example: `<p>2<sup>3</sup> = 8</p>` $\rightarrow$ 2³ = 8

10. **Deleted Text (`<del>`)**: Shows text that has been struck through/deleted.
    * Example: `<p>The price is <del>₹500</del> ₹350.</p>`

11. **Inserted Text (`<ins>`)**: Shows inserted text and automatically underlines it.
    * Example: `<p>I am learning <ins>HTML</ins>.</p>`

12. **Strike text — (`<strike>`)**: Struck-through text but ⚠️ Outdated ,❌ Abandoned

13. **Monospaced font — (`<tt>`)**: Typewriter-style fixed-width text but ❌ Abandoned

14. **Larger text — <big>**: Bumped text up one size but ❌ Abandoned.

---

**Phrase tags:**

|Item|Status|What it does|
|---|---|---|
|Text abbreviation — `<abbr>`|✅ Current|Marks an abbreviation; pair with title for the full expansion: `<abbr title="Hypertext Markup Language">HTML</abbr>`|
|Acronym — `<acronym>`|❌ Abandoned in HTML5. Use `<abbr>` for both abbreviations and acronyms now|Old, separate tag for acronyms specifically|
|Text direction — `<bdo>`|✅ Current|Overrides text direction for a span: `<bdo dir="rtl">This flips right-to-left</bdo>` — pairs with the dir attribute already in Module 2, but `<bdo>` itself is the phrase tag|
|Special terms — `<dfn>`|✅ Current|Marks the defining instance of a term: `<dfn>HTML</dfn>` stands for Hypertext Markup Language|
|Programming variables — `<var>`|✅ Current|Marks a variable name, usually alongside `<code>/<pre>`: `<var>x</var>` = `<var>y</var> + 1`|
|Address — `<address>`|✅ Current|Wraps contact info for a page/article: `<address>Email: amy@example.com</address>` — browsers usually italicize it by default|

---

**Centering Content (Legacy)**:

⚠️ Outdated: `<center>` puts any content — text, an image, a whole table cell — in the center of the page or cell.

*Html code*
```
<center>
  <p>This paragraph is centered.</p>
</center>
```
*Modern approach*: use CSS instead.

*Css code*
```
p { text-align: center; }    /* for text */
div { margin: 0 auto; width: 50%; } /* for a block element */
```
---

**Quotations**

1. `<q>` — inline quote:

Used for short, inline quotes.

*Html code*
```
<p><q>The only way to do great work is to love what you do.</q> — Steve Jobs</p>
```
Output: *“The only way to do great work is to love what you do.” — Steve Jobs*

2. `<blockquote>` — block quote:

Used for longer quotes, entire paragraphs, set apart from the main text.

*Html code*
```
<p>As Albert Einstein once said:</p>
<blockquote>
  <p>Imagination is more important than knowledge.</p>
</blockquote>
```
3. `<cite>` — title or source:

Marks up the title of a work or source. Typically rendered in italics.

*Html code*

`<p>I learn <cite>HTML</cite></p>`

* *cite attribute*

Some elements (like `<q>` and `<blockquote>`) can also take a cite attribute to point to the URL of the source. It doesn't show visually, but screen readers and browsers can use it for extra context.

*Html code*
```
<p>As Steve Jobs once said, <q cite="https://www.brainyquote.com/quotes">Innovation distinguishes between a leader and a follower.</q></p>
```
---

**Code-related Text**

1. `<code>` — inline code:

Used for short, inline snippets of code — variable names, function names, or HTML tags. Tells the browser/search engines "this is programming code, not normal human language."

*Html code* 
```
<pre><code>
function greet() {
  console.log("Hello!");
}
</code></pre>
```

2. `<pre>` — preformatted text:

Preserves all whitespace exactly as written (spaces, line breaks) — the browser normally collapses extra spaces, so use `<pre>` when spacing/formatting matters (like displaying a code block).

`<code>` is often used inside `<pre>` together for multi-line code blocks:

*Html code*
```
<pre><code>
function greet() {
  console.log("Hello!");
}
</code></pre>
```

3. `<kbd>` — keyboard input:

Used in tutorials/documentation to show users exactly what key(s) to press.

*Html code*
```
<p>To copy text, press <kbd>Ctrl</kbd> + <kbd>C</kbd>.</p>
```

4. `<samp>` — sample output:

Used to show sample output from a program or system — e.g. an error message, a computer response.

*Html code*
```
<p>If you forget your password, the screen will say: <samp>Error: Invalid credentials.</samp></p>
```

[⬅️ Previous module 02:Document structure](./document-structure.md)|

[➡️ Next module 04:Lists](./lists.md)
