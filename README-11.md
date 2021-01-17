# Images

* You can control the size of an image using the width and height properties in CSS.


* Centering images

        img.align-center {
        display: block;
        margin: 0px auto;}
        img.medium {
        width: 250px;
        height: 250px;}



* Background Images

        body {
        background-image: url("images/pattern.gif");}

* Repeating Images

    property can have four values: <br>
    repeat  <br>
    The background image is repeated both horizontally and vertically.
    <br>
    repeat-x<br>
    The image is repeated horizontally only .
    <br>
    repeat-y<br>
    The image is repeated vertically only.
    <br>
    no-repeat<br>
    The image is only shown once.        


* Contrast of background images    

High Contrast 

    The majority of photographs have quite a high contrast, which means that they are not ideal for
    use as a background image

Low Contrast 

Screen : 

    To overlay text on an image with high contrast, you can place a
    semi-transparent background color (or "screen") behind the
    text to improve legibility.

<br>

# Practical Information

**Search engine optimization (or SEO)** is the practice of trying to help your site appear nearer the top of search engine results
when people look for the topics that your website covers.

 ### SEO is often split into two areas:
* on-page techniques 
* off-page techniques

<br>

### In every page of your website there are seven key places where keywords (the words people might search on to find your site) can appear in order to improve its findability. On-Page SEO

* Page Title

The page title appears at the top of the browser window or on the tab of a browser. It is specified in the `<title>` element which lives
inside the `<head>` element.

*  URL / Web Address

The name of the file is part of the URL. Where possible, use keywords in the file name.

* Headings

If the keywords are in a heading `<hn>` element then a search engine will know that this page is all about that subject and give it
greater weight than other text.

* Text

Where possible, it helps to repeat the keywords in the main body of the text at least 2-3 times. Do not, however, over-use
these terms, because the text must be easy for a human to read.

*  Link Text

Use keywords in the text that create links between pages (rather than using generic expressions such as "click here").

* Image Alt Text

Search engines rely on you providing accurate descriptions of images in the alt text. This will also help your images show up in the results of image-based
searches.

* Page Descriptions

The description also lives inside the `<head>` element and is
specified using a `<meta>` tag.

<br>

### Here are many steps that will help you identify the right keywords and phrases for your site.

* Brainstorm

It often helps to ask other people what words they would use to
find your site because people less familiar with a topic might use different terms than you. 

* Organize

Group the keywords into separate lists for the different sections or categories of your website.

* Research

There are several tools that let you enter your keywords and then they will suggest additional keywords you might like to
consider, such as:
`www.wordtracker.com` <br>
`www.keyworddiscovery.com`

<br>

### Domain Names & Hosting

In order to put your site on the web you will
need a domain name and web hosting

DOMAIN NAMES WEB HOSTING <br> Your domain name is your web address  There are many websites that allow you to register domain names. Usually you will have to pay an annual fee to keep that domain name. These sites usually have a form that allows you to check whether your preferred domain name is available, and because millions of domain names have already been registered, it might take you a while to find the one that is
right for your site.
<br> 
<br>
So that other people can see your site, you will need to upload it to a web server. Web servers
are special computers that are constantly connected to the Internet. They are specially set up to serve web pages when
they are requested. With the exception of some very large sites, most websites live on web servers run by web hosting
companies. This is usually far cheaper and more reliable than trying to run your own web servers. There are lots of different types of hosting on offer. 


### FTP & Third Party Tools

To transfer your code and images from your computer to your hosting company, you use something known as File Transfer Protocol. 

As the name suggests, File Transfer Protocol (or FTP) allows you to transfer files across the Internet from your computer to the web server hosting your site.

<br>

### Adding Video to Your Pages

To show a video in HTML, use the `<video>` element:

        <!DOCTYPE html>
        <html>
        <body>

        <video width="320" height="240" controls>
        <source src="movie.mp4" type="video/mp4">
        <source src="movie.ogg" type="video/ogg">
        Your browser does not support the video tag.
        </video>

        </body>
        </html>


How it Works <br>
The controls attribute adds video controls, like play, pause, and volume.

It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

The `<source>` element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

The text between the` <video> and </video>` tags will only be displayed in browsers that do not support the `<video>` element.

 <br>


### [Back To README File](https://raghadmustafa96.github.io/reading-notes)
