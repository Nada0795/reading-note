#IMAGES

### You can control the size of an image using the width and height properties in CSS, just like you can for any other box. Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.


### Centering images Using CSS
img.align-center {
display: block;
margin: 0px auto;}
img.medium {
width: 250px;
height: 250px;}


### Background Images
body {
background-image: url("images/pattern.gif");}



### Background Position
body {
background-image: url("images/tulip.gif");
background-repeat: no-repeat;
background-position: center top;}


### shorthand Background
body {
background: #ffffff url("images/tulip.gif")
 no-repeat top right;}



* we can specify the dimensions of images using CSS.
This is very helpful when you use the same sized
images on several pages of your site.

* Images can be aligned both horizontally and vertically
using CSS.

* You can use a background image behind the box
created by any element on a page.

* Background images can appear just once or be
repeated across the background of the box.

* You can create image rollover effects by moving the
background position of an image.

* To reduce the number of images your browser has to
load, you can create image sprites.