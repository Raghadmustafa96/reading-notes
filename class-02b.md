# Introducing CSS
`CSS  `make your web pages more attractive, it allows you to create rules that specify how the content of
an element should appear. <br>

The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

<br>

### BLOCK & INLINE ELEMENTS
`Block level elements ` look
like they start on a new line.
Examples the `<h1>-<h6>, <p>` and `<div>` elements. <br>

`Inline elements ` flow within the text and do not start on a new
line. Examples `<b>, <i>, <img>, <em> and <span>`.

<br>

### Example Styles
* Boxes <br>
Width and height ,
Borders (color, width, and style),
Background color and images,
Position in the browser window .

* Text <br>
Typeface ,
Size,
Color,
Italics, bold, uppercase,
lowercase, small-caps.

<br>

### Using External CSS
`<link> `  element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. 

### Using Internal CSS
`<style> `
You can also include CSS rules within an HTML page by placing
them inside a `<style>` element, which usually sits inside the
`<head>` element of the page. 

> CSS selectors are case sensitive, so they must match element names and attribute values exactly


<br>

### CSS Selectors
* Universal Selector  ` * {}`
* Type Selector  Matches element names  ` h1, h2, h3 {}`
* Class Selector  ` .note {}`
* ID Selector `  #introduction {}`
* Child Selector  ` li>a {}`
* Adjacent Sibling Selector   : Matches an element that is the next sibling of another ` h1+p {}`
* General Sibling Selector ` h1~p {}`


> font-family property is inherited by child elements.
the background-color or border properties; they are not inherited by child elements

<br>


### [Back](https://raghadmustafa96.github.io/reading-notes/class-02)




