# Images, Color, Text


## Images
> great images help make the difference between an average-looking site and a really engaging one.

### Adding Images
`<img>` 

* To add an image into the page you need to use an `<img>` element. This is an empty element (which means there is no closing tag). 

It must carry the following two attributes:
### src
This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. 

### alt
This provides a text description of the image which describes the image if you cannot see it.

### title
You can also use the title attribute with the `<img>` element to provide additional information about the image. 

 `<img>` element use two other attributes that specify its size:

### height
This specifies the height of the image in pixels.

### width
This specifies the width of the image in pixels.

<br>

### Where to Place Images in Your Code
1. before a paragraph
1. inside the start of aparagraph
1. in the middle of a paragraph

<br>

### **Inline elements** sit within a block level element and do not start on a new line. Examples of inline elements include the `<b>, <em>, and <img>` elements.

* If the `<img>` element is inside a block level element, any text or other inline elements will flow around the image.
* If the `<img>` is followed by a block level element then the block level element will sit on a new line

<br>

### Three Rules for Creating Images
* Save images in the right format
* Save images at the right size
* Use the correct resolution

<hr />


## Color
> Color can really bring your pages to life.

### Foreground Color


**The  color  property allows you to specify the color of text inside an element**

You can specify any color in CSS in one of three ways : 

1. rgb values 
These express colors in terms of how much red, green and blue are used to make it up. For example:  rgb(100,100,90)  


1. hex  Codes 
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign.
 For example:  #ee3e80

1. Color names 
There are 147 predefined color names that are recognized by browsers. For example: DarkCyan 

<br>

## background-color
CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box. 
You can specify your choice of background color in the same three ways you can specify foreground colors: 
* RGB values
* hex code
* color names 

If you do not specify a background color, then the background is transparent. 

`body { background-color: rgb(200,200,200);} h1 { background-color: DarkCyan;}`


Every color on a computer screen is created by mixing amounts of red, green, and blue. 

Computer monitors are made up of thousands of tiny squares called pixels. 

When the screen is not turned on, it's black because it's not emitting any light. When it's on, each pixel can be a different color, creating a picture. The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue. 

<br>

## Contrast


1. high Contrast
Text is easier to read when there is higher contrast between background and however,  then too much contrast can make it harder to read,too


1. low Contrast 
Text is harder to read when there is low contrast between background and foreground colors. A lack of contrast is particularly a problem for those with visual impairments and color blindness. It also affects those with poor monitors and sunlight on their screens. 


1. medium Contrast
 For long spans of text, reducing the contrast a little bit improves readability. You can reduce contrast by using dark gray text on a white background or an off-white text on a dark background.

<br>

#### opacity

CSS3 introduces the  opacity property, which allows you to specify  the  opacity  of  an  element and any of its child elements. 
The value is a number between 0.0  and  1.0

<br>
<hr />

## Text

#### techniques That Offer a Wider Choice of Typefaces :

* font-family 
* font-face 
* Service-based Font-Face

#### Bold font-weight
The font-weight property allows you to create bold text. 
<br>
`.credits {`
`font-weight: bold;}`

#### There are two values that this property commonly takes:

* normal

This causes text to appear at a
normal weight.

* bold

This causes text to appear bold.

<br>

#### UpperCase and LowerCase

The text-transform property is used to change the case of text giving it one of the following values:

* uppercase

This causes the text to appear uppercase. <br>
`h1 {` <br>
`text-transform: uppercase;}` <br>

* lowercase

This causes the text to appear lowercase. <br>
`h2 {` <br>
`text-transform: lowercase;}` <br>


<br>


### [Back To README File](https://raghadmustafa96.github.io/reading-notes)