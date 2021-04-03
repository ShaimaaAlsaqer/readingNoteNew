## From the Duckett JS book
+ Chapter 3: “Object Literals” (pp.100-105)
+ Chapter 5: “Document Object Model” (pp.183-242)

#### object
> an object is a standalone entity, with properties and type. Compare it with a chair, for example. A chair is an object, with properties. A chair has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties
> `var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};`

#### DOM Tree
> When a web page is loaded, the browser creates a Document Object Model of the page.
![DOM tree](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)

*getElementById() Method*
`document.getElementById("demo");`
- The getElementById() method returns the element that has the ID attribute with the specified value.
- Returns null if no elements with the specified ID exists.
- This method is the most common methods in the HTML DOM, and is used to manipulate, or get info from, an element on your document.

*querySelector() and querySelectorAll()*
`querySelector()
querySelectorAll()`
- The querySelector() method returns the first element that matches a specified CSS selector(s) in the document.
- querySelector() method only returns the first element that matches the specified selectors. To return all the matches, use the querySelectorAll() method

*groups of element nodes*
* method can return more than one node, it will always return a Nodelist "collection of nodes"
* need to select the element you want from this list using an index number
* `getEl ement sByClassName( 1class 1)`
> Selects one or more elements given the value of their class attribute.
>  HTML must have a class attribute for it to be selectable.
This method is faster than querySelectorAll()
* getEl ementsByTagName( 'tagName')`
> Selects all elements on the page with the specified tag name.
This method is faster than querySelectorAll()
> `getElementsByTagName('h1' )`
* using innerHTML property, to access and amend the contents of an element, including any child elements
> `var elContent = document.getElementByld('one').innerHTML;`
* document.write()
> The object write() method is a simple way to add content that was not in the original source code to the page, but its use is rarely advised
> quick and easy way to show beginners how content can be added to a page
> DISADVANTAGES
> > It only works when the page initially loads.
> > If you use it after the page has loaded it can:
> > >  Overwrite the whole page
> > > Not add the content to the page
> > > Create a new page
> > It can cause problems with XHTML pages that are strictly validated.
> > This method is very rarely used by programmers these days and is genera lly frowned upon