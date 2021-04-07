#### From the Duckett HTML book:

###### Chapter 7: “Forms” (p.144-175)
###### Chapter 14: “Lists, Tables & Forms” (pp.330-357)
&  Form Controls

types of form controls use to collect information from visitors site:
* adding text:
> text input => single line, to add for example email addresses and name
> password input => like a single, line text box but it masks the characters entered
> text area => multi-line, for longer areas of text, like messages and comments

* making choices:
> radio buttons => for use when a user must select one of a number of options
> checkboxes => the user can select and unselect one or more options
> drop-down boxes => user can pick one of a number of options from a list

* submitting forms
> submit buttons => to submit data from your form to another web page
> image buttons => similar to submit buttons but they allow to use an image

* uploading files
> file upload => allows users to upload files to the website, like image

* <forms>
`<form action="http://www.example.com/subscribe.php"
method="get">
<p>This is where the form controls will appear.
</p>
</form>`
> form => carry the action attribute and have a method and id attribute
> action=> every <form> requires an action attribute. Its value  URL for the page on the server that will receive the information in the form when it is submitted.
> method  => forms can be sent using one of two methods: get or post
* <input> 
`<form action="http://www.example.com/login.php">
<p>Username:
<input type="text" name="username" size="15"
maxlength="30" />
</p>
</form>`
> input use to create different form controls
> type => determine what kind of input they will be creating `type=text`
> `type="password"`  attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. They are hidden in this way so that if someone is looking over the user's shoulder, they cannot see sensitive data such as passwords
> <textarea> element is used to create a mutli-line text input. Unlike other input elements this is not an empty element. It should therefore have an opening and a closing tag
> `type="radio"` Radio buttons allow users to pick
just one of a number of option
> `type="checkbox"` => Checkboxes allow users to select one or more options in answer to a question
> <select> a drop down list box (also known as a select box) allows users to select one option from a drop down list.
> <option>  element is used to specify the options that the user can select from. The words between the opening <option> and closing </option> tags will be shown to the user in the drop down box
> type="submit" => The submit button is used to send a form to the server

**********
* `list-style-type` => allowsto control the shape or style of a bullet point
> Unordered Lists
> > none
> > disc
> > circle
> > square
> Ordered Lists
> > decimal
> > > 1 2 3
> > decimal-leading-zero
> > > 01 02 03
> > lower-alpha
> > > a b c
> > upper-alpha
> > >A B C
> > lower-roman
> > >i. ii. iii.
> > upper-roman
> > > I II III