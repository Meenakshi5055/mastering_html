# Module-04: Lists

[⬅️ Back to index](./readme.md)
---
**Lists are used to display information neatly**

Lists are three types:
* **Unordered list[`<ul>`]:** Displays item with bullet points(.)
* **Ordered list[`<ol>`]:** Displays items with numbers(1).
* **Description list[`<dl>`]:** To show a term and its description.
---
1. **Unordered list:**
Which displays item with bullet points for organization.

*`<li>`-list of items* used inside of a tag.

 *Html code*:
 ```
<ul>
<li>Apple</li>
<li>Watermelon</li>
<li>Berries</li>
</ul>
```
[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)

[▶️ to run the code in VS code](https://code.visualstudio.com/)

* Use unordered lists when items can be scrambled without changing the meaning. Items are grouped but hold equal priority.

**2. Ordered list:**
Which displays items with numbers for organization.

*Html code*
```
<ol>
<li>Wake up</li>
<li>Exercise</li>
<li>Brush teeth</li>
</ol>
```
[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)

[▶️ to run the code in VS code](https://code.visualstudio.com/)

* Use ordered lists when the sequence of items matters. Changing the order alters the meaning or success of the information.

**Attributes**

* *Type attribute:*
  For changing the numbering style with different value as per us.

  | Value | Style | Example |
  | --- | --- | --- |
  | 1 | Numbers(default) | 1,2,3 |
  | A | Uppercase letters | A,B,C |
  | a | Lowercase letters | a,b,c |
  | I | Upper  roman letters | I,II,III |
  | i | Lower roman letters | i,ii,iii |

  
  *Html code*
```
<ol type='i'>
<li>HTML</li>
<li>CSS</li>
<li>Java-script</li>
</ol>
```
[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)

[▶️ to run the code in VS code](https://code.visualstudio.com/)

*press full-stop (" . ") to run the code, it directly takes you to the VS-Code.*

* *Start attribute:*
  For continuing the lists which is started already/before from the next point.

 *Html code*
  ```
<ol start='4'>
<li>Drink milk</li>
<li>Study</li>
<li>Take bath</li>
</ol>
```
[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)

[▶️ to run the code in VS code](https://code.visualstudio.com/)

*Or else press full-stop (" . ") to run the code, it directly takes you to the VS-Code.*

* Useful when continuing instructions across different pages or sections.*

* *Reversed attribute:*
  Counts down-wards instead of upwards, like 9 8 7 6 5 4 3 2 1 stop.

   *Html code*
```
<ol reversed>
<li>Third</li>
<li>Second</li>
<li>First</li>
</ol>
```
[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)

[▶️ to run the code in VS code](https://code.visualstudio.com/)

*Or else press full-stop (" . ") to run the code, it directly takes you to the VS-Code.*
*During competitions, countdowns etc., 

3. **Description list:**
A description list (the <dl> HTML tag) is a semantic structure used to pair terms with their corresponding descriptions.
Giving description for the term. to show term and description.
* `<dl>` Starts the overall list, a wrapper container. 
* `<dt>` Defines the term(word)
* `<dd>` Defines the description(meaning)

 *Html code*
  ```
<dl>
<dt>HTML</dt>
<dd>The markup language used to structure web pages.</dd>
<dt>CSS</dt>
<dd>The language used to style the webpage</dd>
</dl>
```
[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)

[▶️ to run the code in VS code](https://code.visualstudio.com/)

*Or else press full-stop (" . ") to run the code, it directly takes you to the VS-Code.*

- Use description list for precise, structured key-value pairings where information is directly linked. Like glossaries, metadata, FAQ pages.

- Avoid description list when data is narrative, sequential, or strictly tabular. Like step-by-step instructions, simple bullet points.

**Nesting Lists:**
List inside a list, for better organization.

*Html code-1*
  ```
<ol>
<li>Front-end
<ul>
<li>HTML</li>
<li>CSS</li>
<li>Java-script</li>
</ul>
</li>
<li>Back-end
<ul>
<li>Python</li>
<li>SQL</li>
<li>Java</li>
</ul>
</li>
</ol>
```

*Html code-2*
```
<ol>
  <!-- Step 1 (Ordered) -->
  <li>
    <strong>Prepare the workspace</strong>
    <!-- Nested Unordered List -->
    <ul>
      <li>Sanitise the countertops</li>
      <li>Gather all measuring tools</li>
      <li>Sharpen the chef's knife</li>
    </ul>
  </li>

  <!-- Step 2 (Ordered) -->
  <li>
    <strong>Measure the ingredients</strong>
    <!-- Nested Unordered List -->
    <ul>
      <li>250g all-purpose flour</li>
      <li>10g active dry yeast</li>
      <li>5g fine sea salt</li>
    </ul>
  </li>

  <!-- Step 3 (Ordered) -->
  <li>
    <strong>Mix and knead the dough</strong>
  </li>
</ol>
```


[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)

[▶️ to run the code in VS code](https://code.visualstudio.com/)

*Or else press full-stop (" . ") to run the code, it directly takes you to the VS-Code.*

---

[⬅️ Previous module 03: Text-formatting](./text-formatting.md)|

[➡️ Next module 05: Links](./links.md)
 








