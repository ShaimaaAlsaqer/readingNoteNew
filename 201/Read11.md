#### From the Duckett HTML book:

* Chapter 16: “Images” (pp.406-427)
* Chapter 19: “Practical Information” (476-492)

*** we can controlling size of image in css using: ***
> width
> hight

*aligning images using CSS*
> float can move the element to left or right
> float property is added to the class that was created to represent the size of the image
`img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}`

*** By default, images are inline elements ***
> background-image property allows you to place an image behind any HTML element
`body {
background-image: url("images/pattern.gif");}`

***this is the way to put background to element using css***
`p {
background-image: url("images/pattern.gif");}`

*** The background-repeat property can have four values:***
> repeat : The background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn't used).
> repeat-x : The image is repeated horizontally only (as shown in the first example on the left).
> repeat-y : The image is repeated vertically only.
> no-repeat : The image is only shown once.

*** The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page.It can have one of two values: ***
> fixed: The background image stays in the same position on the page.
> scroll: The background image moves up and down as the user scrolls up and down the page.

*** background-position ***
This property has a pair of values. 
> The first represents the horizontal position
> the second represents the vertical.
> > left top
> > left center
> > left bottom
> > center top
> > center center
> > center bottom
> > right top
> > right center
> > right bottom
`body {
background-image: url("images/tulip.gif");
background-repeat: no-repeat;
background-position: center top;}`

##### Search Engine Optimization (SEO )
* SEO: is the practice of trying to help the site appear nearer the top of search engine results when people look for the topics that your website covers.
* On-page techniques are the methods you can use on your web pages to improve their rating in search engines.

***  On-page SEO *** 
> page title:  appears at the top of the browser window or on the tab of a browser. It is specified in the <title> element which lives inside the <head> element
> URL / Web Address:  The name of the file is part of the URL. Where possible, use keywords in the file name
> Headings: If the keywords are in a heading <hn> element then a search engine will know that this page is all about that subject and give it greater weight than other text
> Text :  Where possible, it helps to repeat the keywords in the main body of the text at least 2-3 times
> Link Text:  Use keywords in the text that create links between pages
> Image Alt Text: help your images show up in the results of image-based searches.
> Page Descriptions:  The description also lives inside the <head> element and is specified using a <meta> tag

###### How Many People Are Coming to Your Site?
* Visits
> This is the number of times people have come to your site. If someone is inactive on your site for 30 minutes and then looks at another page on your site, it will be counted as a new visit.
* Unique Visits
> This is the total number of people who have visited your site over the specified period.
* Page Views
> The total number of pages all visitors have viewed on your site
* Pages per Visit
> The average number of pages each visitor has looked at on your site per visit.
* Average Time on Site
> The average amount of time each user has spent on the site per visit.
* Date Selector
> Using the date selector in the top right hand corner of the site, you can change the period of time the reports display
