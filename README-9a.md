# Forms
There are several types of form controls that you can use to collect information from visitors to your site.
* ADDING TEXT(Text or Password input ,Text area)
* Making Choices: (Radio buttons,Checkboxes,Drop-down boxes)
* Submitting Forms
* Uploading Files

To differentiate between various pieces of inputted data, informationis sent from the browser to the server using name/value pairs.
example, when form asks for the visitor's username 


## Form Structure

`<form>`
* Form controls live inside a `<form>` element. This element
should always carry the action attribute and will usually have a method and id attribute too.

* action
Every `<form>` element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

* method
Forms can be sent using one of two methods: get or post.
With the get method, the values from the form are added to the end of the URL specified in the action attribute. 

        <form action="http://www.example.com/subscribe.php"
        method="get">
<br>

* Text Input
used to create several different form controls.  
`<input type="text" name="username" size="15"`
 `maxlength="30" />`

 * Password Input
`<input type="password" name="password" size="15"`
 `maxlength="30" />`

* text area : is used to create a mutli-line text input
`<textarea name="comments" cols="20" rows="4">Enter`
 `your comments...</textarea>`

* Radio Button
 Radio buttons allow users to pick just one of a number of options

* Checkboxes 
allow users to select (and unselect) one or more options in answer to a question.

* A drop down list box (also
known as a select box) allows users to select one option from a
drop down list.  

* File Input Box : If you want to allow users to upload a file (for example an image, video, mp3, or a PDF), you will need to use a file input
box

*  submit button is used to send a form to the server. 

* If you want to use an image for he submit button, you can give the type attribute a value of image. 
 `<input type="image" src="images/subscribe.jpg"`
 `width="100" height="20" />`

 * If you want to create a single line text box for search queries,
`<input type="search" name="search" />`
`<input type="submit" value="Search" />`

 <br>

### [Back](https://raghadmustafa96.github.io/reading-notes/README-9)
