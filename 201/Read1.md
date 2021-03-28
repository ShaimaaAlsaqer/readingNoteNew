## Duckett HTML book
#### Chapter 2: “Text” (pp.40-61)
*HEADINGS*
on html we have a 6 level of heading
<h1># is the main heading tag, we use it for the important heading</h1>
<h2>## used for subheadings
<h3>###
<h4>####
<h5>#####
<h6>######

*Paragraphs*
* Paragraph opening tag and closing tag <p></p>
* if we have more than one paragreph By default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

*Bold*
<b></b> make characters appear bold.
``<p> we use the b tag to make the characters <b>bold</b></p>``

*Italic*
<i></i> make characters appear italic
``<p> we use the b tag to make the characters <i>bold</i></p>``

*Superscript and Subscript*
> The <sup> tag defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1].
> The <sub> tag defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O.
>> ``<p>This text contains <sub>subscript</sub> text.</p>
<p>This text contains <sup>superscript</sup> text.</p>``

*Line Breaks and Horizontal Rules*
>line breaks <br/>
>><br/> inserts a single line 
>> <br/> is an empty tag which means that it has no end tag.

>Horizontal Rules
>><hr/> used to create a break between themes
>><hr/> is an empty tag which means that it has no end tag.
>>> ``<p>Venus is the only planet that rotates clockwise.</p>
<hr />
<p>Jupiter is bigger than all the other planets combined.</p>``

*Strong and Emphasis*
> Strong
>> <strong> tag indicates that its content has strong importance
>>By default, browsers will showthe contents of a <strong>element in bold
>>> <strong> importance</strong>

>>Emphasis
>>By default browsers will show the contents of an <em> element in italic
>><em> tag indicates emphasis that subtly changes the meaning of a sentence
>>> <em>italic</em>

*Quotations*
we have 2 tag used for marking up quotations:
* <blockquote> tag is used for longer quotes that take up an entire paragraph
``<blockquote cite="http://en.wikipedia.org/wiki/Winnie-the-Pooh">
<p>paragtapg</p> </blockquote>``
* <q> used for shorter quotes that sit within a paragraph
``<p>paragraph, <q>Quotations tag</q></p>``

*abbreviation and acronyms*
<abbr> to make abbreviation or an acronym
``The <abbr title="World Health Organization">WHO</abbr> was founded in 1948``

*Citations and Definitions*
> <cite> used to referencing a piece of work such as a book, film or research paper
>><p> <cite> A Brief History of Time</cite> by Stephen Hawking has sold over ten million copies worldwide.</p>

><dfn> tag used to indicate the defining instance of a new term. 
>><p>A <dfn>black hole</dfn> is a region of space from which nothing, not even light, can escape.</p>

*Author Details*

