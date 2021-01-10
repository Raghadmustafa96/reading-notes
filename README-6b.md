# Document Object Model

> The Document Object Model (DOM) specifies how browsers 
 should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 

* The DOM is neither part of HTML, nor part of JavaScript, it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas: 

1. making A model of the HTML page .
1. accessing and changing the HTML page 

### making A model of the HTML page

* creates a model of the page in memory. 
* The DOM specifies the way in which the browser should structure this model using a DOM tree.
* The DOM is called an object model because the model (the DOM tree) is made of objects.
* Each object represents a different part of the page loaded in the browser window.

<br>

### THE DOM TREE IS A MODEL OF A WEB PAGE 

As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes. 

* THE DOCUMENT NODE

HTML is represented by its own DOM node.
At the top of the tree a document node is added; it represents the entire page  When you access any element, attribute, or text node, you navigate to it via the document node. It is the starting point for all visits to the DOM tree. 

* ELEMENT NODES
To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. 

> Relationships between the document and all of the element nodes are described using the same terms as a family tree: parents, children, siblings, ancestors, and descendants. (Every node is a descendant of the document node.) .

* Each node is an object with methods and properties.
Scripts access and update this DOM tree . Any changes made to the DOM tree are reflected in the browser.  

### WORKING WITH THE DOM TREE <br>
Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
1. Use its text content, child elements, and attributes. 



<br>

### [Back](https://raghadmustafa96.github.io/reading-notes/README-6)