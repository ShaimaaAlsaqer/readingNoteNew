## Duckett HTML book
#### Chapter 2: “Text” (pp.40-61)
HEADINGS: on html we have a 6 level of heading from h1 to h6 
heading one is the main heading tag, we use it for the important heading
___________________________________________________________________________________________________________

*Paragraphs*
* Paragraph opening tag and closing tag <p></p>
* if we have more than one paragreph By default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.
______________________________________________________________________________________________

*Bold*
<b></b> make characters appear bold.
<p> we use the b tag to make the characters <b>bold</b></p>
______________________________________________________________________________________________

*Italic*
<i></i> make characters appear italic
``<p> we use the b tag to make the characters <i>bold</i></p>``
______________________________________________________________________________________________________

*Superscript and Subscript*

1. The <sup> tag defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1].
2. The <sub> tag defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O.
<p>This text contains <sub>subscript</sub> text.</p> <p>This text contains <sup>superscript</sup> text.</p>
___________________________________________________________________________________________________________

*Line Breaks and Horizontal Rules*
line breaks <br/>
- <br/> inserts a single line 
- <br/> is an empty tag which means that it has no end tag.
_________________________________________________________________________________________________________________

Horizontal Rules
* <hr/> used to create a break between themes
* <hr/> is an empty tag which means that it has no end tag.
* <p>Venus is the only planet that rotates clockwise.</p> <hr /> <p>Jupiter is bigger than all the other planets combined.</p>
__________________________________________________________________________________________________________________

*Strong and Emphasis*
Strong
- <strong> tag indicates that its content has strong importance
- By default, browsers will showthe contents of a <strong>element in bold
- <strong> importance</strong>
__________________________________________________________________________________________
Emphasis
- By default browsers will show the contents of an <em> element in italic
- <em> tag indicates emphasis that subtly changes the meaning of a sentence
- <em>italic</em>
__________________________________________________________________________________________
*Quotations*
we have 2 tag used for marking up quotations:
- blockquote tag is used for longer quotes that take up an entire paragraph <blockquote cite="http://en.wikipedia.org/wiki/Winnie-the-Pooh"> <p>paragtapg</p> </blockquote>
- q used for shorter quotes that sit within a paragraph like<p>paragraph, <q>Quotations tag</q></p>
__________________________________________________________________________________________


*abbreviation and acronyms*
- abbr to make abbreviation or an acronym
The <abbr title="World Health Organization">WHO</abbr> was founded in 1948
_________________________________________________________________________________________________________________

*Citations and Definitions*
cite used to referencing a piece of work such as a book, film or research paper <p> <cite> A Brief History of Time</cite> by Stephen Hawking has sold over ten million copies worldwide.</p>

dfnntag used to indicate the defining instance of a new term. 
<p>A <dfn>black hole</dfn> is a region of space from which nothing, not even light, can escape.</p>
<ins> tag can be used to show content that has been inserted into a document
<del> tag can show text that has been deleted from it
<s> tag indicates something that is no longer accurate or relevant
__________________________________________________________________________________________
__________________________________________________________________________________________

*Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)*
CSS stands for Cascading Style Sheets
- p {font-family: Arial;} that is mean all paragraph will shown as a font Arial
__________________________________________________________________________________________

- h1, h2, h3 { font-family: Arial; color: yellow;} thats mean all h1,h2,h3 tag all heading will shown as a font Arial
__________________________________________________________________________________________

- link tag <link>

 1. is empty tag
 2. link tag is used to link external style sheets
 21. href: path to the CSS file
 22. type : type of document being linked to
 23. rel: relationship between the HTML page and the file it is linked to.
__________________________________________________________________________________________
 to make css we can put it inside head tag in style tag
__________________________________________________________________________________________
 color and background-color in CSS

 1. rgb values: red green blue like rgb(100,90,100)
 2. hex codes like #ee3e80
 3. color names like black
_______________________________________________________________________________________________________

# From the Duckett JS book
#### Chapter 2: “Basic JavaScript Instructions” (pp.53-84)
* statement: statements should end with a semicolon
* comments in JavaScript // this for one line, and this for more than one line/* */
* variables are containers for storing data values(var nameOfVariables=VarValue;)
* array: (var arrayType= [red,black,blue];)
______________________________________________________________________________________________

## Chapter 4: “Decisions and Loops” only up to the section on switch statements (pp.145-162)
***comparision operator***

logical operator return true or false
__________________________________________________________________________________________
comparision operator
1. and &&
2. or ||
3. not !
__________________________________________________________________________________________
we have if statement, if else statement, and switch statement