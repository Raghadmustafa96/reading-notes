# Boxes
>  CSS treats each HTML element as if it lives in its own box. 

#### we can set several properties that affect the appearance of these boxes.
* Control the dimensions of your boxes
* Create borders around boxes
* Set margins and padding for boxes
* Show and hide boxes

## Box Dimensions
width, height

`div.box {` <br>
`height: 300px;` <br>
`width: 300px;` <br>
`background-color: #bbbbaa;}` <br>

<br>

## Limiting Width
min-width, max-width

`td.description {` <br>
`min-width: 450px;` <br>
`max-width: 650px;` <br>
`text-align: left;` <br>
`padding: 5px;` <br>
`margin: 0px;}` <br>

<br>

## Limiting Height
min-height, max-height

`p {` <br>
`min-height: 10px;` <br>
`max-height: 30px;}` <br>

<br>

## Overflowing Content
overflow

The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
* hidden <br>
This property simply hides any extra content that does not fit in the box.

* scroll <br>
This property adds a scrollbar to the box so that users can scroll to see the missing content.

`p.one {` <br>
`overflow: hidden;}` <br>
`p.two {` <br>
`overflow: scroll;}` <br>

<br>

## Border, Margin & Padding
* Border <br>
Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

* Margin <br>
Margins sit outside the edge of the border.

* Padding <br>
Padding is the space between the border of a box and any content contained within it.

<br>

## Change Inline/Block
display

### The values this property can take are:

* inline <br>
This causes a block-level element to act like an inline element.

* block <br>
This causes an inline element to act like a block-level element.

* inline-block <br>
This causes a block-level element to flow like an inline element, while retaining other features of a block-level element.

* none <br>
This hides an element from the page. In this case, the element acts as though it is not on the page at all 


<br>

### [Back](https://raghadmustafa96.github.io/reading-notes/README-3)