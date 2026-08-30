## Module 1: Introduction to HTML

**What is HTML?**

*HTML stands for HyperText Markup Language.*

* HyperText — text that contains links (hyperlinks) to other text/pages. It's what lets you jump from one page to another on the web.
* Markup — using tags to tell the browser how to display content. Tags themselves are invisible in the final page; they just describe structure.
* Language — HTML is not a programming language. It has no logic, loops, or conditions. It's a markup language: it only describes structure and content.

**Html code**

`<h1>Welcome to my website</h1>`

Here `<h1>` and `</h1>` are tags, and "Welcome to my website" is the content they wrap.

**A Bit of History**

* *Tim Berners-Lee* is credited as the father of HTML — he created it in 1991 while working at CERN.
* It was invented mainly so scientists could share information over the internet easily, by linking documents together.
* HTML grew alongside the WWW (World Wide Web), web browsers, and web servers — all four came up together as the foundation of the modern web.

**How a Browser Reads HTML**

The browser reads your HTML tags and figures out what each part of the page is:
> "This is a heading, this is a link, this is a paragraph" → then it renders (displays) the page accordingly.

You write the structure; the browser handles turning it into a visual page.

**Why Learn HTML?**

* It's the *skeleton* of every webpage — even sites built with frameworks like React eventually render down to HTML.
* Pairs with CSS (styling/appearance) and JavaScript (behavior/interactivity) to form the three core web technologies.
* It's beginner-friendly: no compiler, no complex setup — just a text editor and a browser.

**Versions of HTML**
| Version | Notes |
| --- | --- |
| HTML | Original version, 1991 |
| HTML 2.0–4.01 |Added tables, frames, forms, scripting support over the years |
| XHTML | A stricter, XML-based version of HTML (mostly historical now) |
| HTML5 | Current standard — added semantic tags, native audio/video, canvas, form validation, and more |

Throughout this repo, we're learning and writing HTML5, which is what every `<!DOCTYPE html>` declaration refers to.

**Environment Set-up**
1. Offline applications(Desktop editors):

These apps run directly on your computer without requaring an internet connection.
  * *VS-Code*(Visual Studio code):The industry standard editor for web development. Free, powerful,and customizable.
  * *Sublime Text*:A lightweight, fast text editor with high performance.
  * *Notepad++(Windows)*:A simple editor with high  performance. 
2. Online Code Runners(No installation required):

These platforms require  zero installation-users can click a link, type HTML code, and immediately view the rendered output inside their browser. 
  * *CodePen(codepen.io)*: An online editor for HTML, CSS, and JavaScript with live side-by-side rendering.
  * *JSFiddle(jsfiddle.net)*: A lightweight online playground for sharing and testing HTML snippets instantly.
  * *StackBlitz(stackblitz.com)*: A full web-based IDE powered by Visual Studio Code that runs entire web projects in the browser.
   
3. Setting Up HTML in VS Code (Step-by-Step)
Install VS Code: 

Download and install Visual Studio Code from code.visualstudio.com.
* *Login into*: Using GitHub or email id login into it which help you to save the files and use it.
* *Open a Project Folder*: Open VS Code \rightarrow Click File \rightarrow Open Folder... \rightarrow Select or create a folder for your HTML projects.
* *Create an HTML File*: Click the New File icon in the left file explorer and name it index.html (or filename.html).
* *Add Extensions*:On left side of the screen you can see four square shapes and that is extensions.Search for live server and install it.
* *Generate the HTML Boilerplate*: Type ! (an exclamation mark) inside your blank .html file and press Tab or Enter. VS Code will automatically generate the foundational document structure (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).

Write Your HTML Code: Add your content between the `<body>` and `</body>` tags.

For better installation instructions search online.

---

During lessons I provided run button for running the program. so copy the text and click on the run button and it takes to the editor screen space it and you see the output. 

[◀️ Run the code](https://meenakshi5055.github.io/mastering_html/)

*Or else press full-stop " . " to run the code, it directly takes you to VS-code*

---

[⬅️ Back to homepage: Index](./readme.md)|

[➡️ Next module 02:Document structure](./document-structure.md)
