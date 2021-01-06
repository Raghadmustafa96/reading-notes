# Links

### Links are the defining feature of the web because they allow you to move from
* Links are created using the `<a>` element. 
* Users can click on anything between the opening `<a>` tag and the closing `</a>` tag. 
* You specify which page you want to link to using the href attribute.

       `<a href="http://www.imdb.com">IMDB</a>`

<br>

### Linking to Other Pages on the Same Site   
*  Links are created using the `<a>` element which has an attribute called `href` . The value of the href attribute is the page that you want people to go to when they click on the link.

*  Users can click on anything that appears between the opening `<a>` tag and the closing `</a>` tag and will be taken to the page specified in the href attribute.

* When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL.    `<li><a href="http://www.empireonline.com">Empire</a></li>`

> Browsers show links in blue with an underline by default.

<br>

## Linking to Other Pages on the Same Site

* When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.

* If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file.

              <p> <br>
               <ul> <br>
               <li><a href="index.html">Home</a></li> <br>
               <li><a href="about-us.html">About</a></li> <br>
               <li><a href="movies.html">Movies</a></li> <br>
               <li><a href="contact.html">Contact</a></li> <br>
               </ul> <br>
              </p> <br>


* **Relative URLs** :  can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

### Relative Link Type
* Same Folder    `<a href="reviews.html">Reviews</a>`
* Child Folder   `<a href="music/listings.html">Listings</a>`
* Grandchild Folder  `<a href="movies/dvd/reviews.html">Reviews</a>`
* Parent Folder   `<a href="../index.html">Home</a>`
* GrandParent Folder `<a href="../../index.html">Home</a>`


<br>

## Email Links
`mailto:`
* To create a link that starts up the user's email program andaddresses an email to a specified email address, you use the `<a>` element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to. 

* an email link looks just like anyother link but, when it is clicked on, the user's email programwill open a new email message and address it to the person specified in the link  `<a href="mailto:jon@example.org">Email Jon</a>`

## Opening Links in a New Window

`target`

* If you want a link to open in a new window, you can use the `target` attribute on the opening `<a>` tag. The value of thisattribute should be `_blank.`   `<a href="http://www.imdb.com" target="_blank">`

## Linking to a Specific Part of the Same Page
* To link to an element that uses an id attribute you use the `<a>` element again, but the value of the href attribute starts with
the # symbol, followed by the value of the id attribute of the element you want to link to. In example, `<a href="#top">` links to the `<h1>` element at the top of the page whose id attribute has a value of top.

`<h1 id="top">Film-Making Terms</h1>` <br>
`<p><a href="#top">Top</a></p>` <br>
 
 <br>

### [Back](https://raghadmustafa96.github.io/reading-notes/README-4)



