From the Duckett HTML book
Chapter 3: “Lists” (pp.62-73)
Type of List:
- order list <ol></ol>
- un order list <ul></ul>
- each item in the list is placed between <li></li>
- definition list <dl></dl>
- Inside the <dl> element you will usually see pairs of <dt> and <dd> elements.
- <dt> used to contain the term being defined
- <dd> used to contain the the difinition
- in nested list we can put a second list inside an <li> element to create a sublist or nested list
_________________________________________________________________________________________

Chapter 13: “Boxes” (pp.300-329)
Box Dimention
- By default a box is sized just big enough to hold its contents. To set your own dimensions we use height and width properties.
- The most popular ways to specify the size of a box are to use pixels, percentages, or ems.

Limiting width
- min-width property specifies the smallest size a box can be displayed at when the browser window is narrow
- max-width property specifies the maximum width a box can stretch to when the browser window is wide.

Limiting height
- min-height and max-height properties to limit the width and height

overflow property:
overflow property tells the browser what to do if the content contained within a box is larger than the box itself.

overflow  have one of two values:
- hidden: this propertyhides any extra content that does not fit in the box
- scroll: this property adds a scrollbar to the box so that users can scroll to see the missing content

Padding, Border,Margin:
- Padding:specify how much spaceshould appear between the content of an element and its border
- Border: A border that goes around the padding and content
- Margin: Clears an area outside the border(the margin is transparent)(controls the gap between boxes)
- border: border property allows to specify the width, style and color of a border in one property
- text-align: center: put the text in the center
_________________________________________________________________________________________

From the Duckett JS book
Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)
Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)
Array
- array: type of variable. It doesn't just store one value; it stores a list of values
var colors;
colors= ['red', 'blue','black'];

values in array
1 numbering items in array: each item in array is automatically given a number called an index
2 Accessing items in array like colors [ 2];
3 number items in array like colors. length;