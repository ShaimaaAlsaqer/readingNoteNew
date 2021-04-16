#### From the Duckett HTML book:
> Introduction (pp.2-11)
> HTML Chapter 1: “Structure” (pp.12-39)
> HTML Chapter 8: “Extra Markup” (p.176-199)
> HTML Chapter 17: “HTML5 Layout” (pp.428-451)
> HTML Chapter 18: “Process & Design” (pp.452-475)
> From the Duckett JS book:

* HTML Describes the Structure of Pages
* the HTML code (in blue) is made up of characters that live inside angle brackets, these are called HTML elements.
* Tags act like containers. They tell you something about the information that lies between their opening and closing tags.
`<html>
<body>
<h1>This is the Main Heading</h1>
<p>This text might be an introduction to the rest of the page. And if the page is a long one it might be split up into several sub-headings.<p>
<h2>This is a Sub-Heading</h2>
<p>Many long articles have sub-headings so to help you follow the structure of what is being written.
There may even be sub-sub-headings(or lower-level headings).</p>
<h2>Another Sub-Heading</h2>
<p>Here you can see another sub-heading.</p>
</body>
</html>`

* Attributes
> Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign
`<p lang="en-us"> paragraph in english</p>`
`<p lang="fr"> paragraph in Francis</p>`

*body, head,title*
> <body>
> > body element: Everything inside this element is shown inside the main browser window.

> <head>
> > before the <body> element you will often see a <head> element. This contains information about the page.

> <title>
> > usually <title> element be inside the <head> element.
> > The contents of the <title> element shown in the top of the browser, or above it usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time)
> > Anything written between the <title> tags will appear in the title bar (or tabs) at the top of the browser window, highlighted in orange here

### The Evolution of HTML
Since the web was first created, there have been several different versions of HTML
> at the first html 4 released 1997
> then XHTML 1.0 released 2000
> HTML5 released 2000
> > HTML5, web page authors do not need to close all tags, and new elements and attributes will be introduced. At the time of writing, the HTML5 specification had not been completed, but the major browser makers had started to implement many of the new features, and web page authors were rapidly adopting the new markup

* DOCTYPE : because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using
* comment in html <!-- -->
>  comment in the code will not be visible in the user's browser, you can add the text between these characters `<!-- comment goes here -->`
> It is a good idea to add comments to your code because, no matter how familiar you are with the page at the time of writing it, when you come back to it later (or if someone else needs to look at the code), comments will make it much easier to understand.
> Comments can also be used around blocks of code to stop that code from being displayed in the browser

* id
> every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on thepage. Its value should start with a letter or an underscore (not a number or any other character)
> It is important that no twoelements on the same page have the same value for their idattributes (otherwise the value is no longer unique)

* class
> every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page. For example, 
> you might have some paragraphs of text that contain information that is more important than others and wantto distinguish these elements, or you might want to differentiatebetween links that point to other pages on your own site and links that point to external sites

* block elements
> some elements will always appear to start on a new line in the browser window. These are known as block level elements
> Examples of block elements:
> > <h1>
> > <p>
> > <ul>
> >
> > <li>

* inline elements
> Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements
> Examples of inline elements:
> > <a>
> > <b>
> > <em>
> > <img>
* Grouping Text and Elements In a Block
> <div> element allows you to group a set of elements together
in one block-level box

* <iframe>
> iframe is like a little window that has been cut into your page and in that window you can see another page. The term iframe is an abbreviation of inline frame.

every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is


#### Introduction
> JS Chapter 1: “The ABC of Programming” (pp.11-52)
A script is a series of instructions that a computer can follow to achieve a goal

> <script> Tag In HTML, JavaScript code is inserted between <script> and </script> tags
> Each time the script runs, it might only use a subset of
all the instructions.
> to writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task
> > a flowchart can help

JavaScript is designed on a simple object-based paradigm. An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method.

Each object can have its own:
+ Properties
+ Events
+ Methods

* object and method in javascript
`function myFunction() {document.write("Hello World!");}`

* It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension
