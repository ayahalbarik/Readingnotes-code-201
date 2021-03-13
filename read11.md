# Audio and video
The <video> and <audio> elements allow us to embed video and audio into web pages. As we showed in Video and audio content, a typical implementation looks like this:

**<video controls>**
  //<source src="rabbit320.mp4" type="video/mp4">
  //<source src="rabbit320.webm" type="video/webm">
  //<p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
//</video>

The <video> element has a number of attributes which allowyou to control video playback:
*src*
This attribute specifies the pathto the video. (The example video
is in H264 format so it will only
work in IE and Safari.)
posterThis attribute allows you tospecify an image to show while
the video is downloading or untilthe user tells the video to play.
width, heightThese attributes specify the size of the player in pixels.*controls*
When used, this attribute indicates that the browser should supply its own controls for playback. autoplay When used, this attribute specifies that the file should play automatically.loop
When used, this attribute
indicates that the video should
start playing again once it has
ended.


## what about HTML images
you  can improve the design and the appearance of a web page
//<img src="pic_trulli.jpg" alt="Italian Trulli">
 in the link you can see ,The <img> tag has two required attributes:

1. src - Specifies the path to the image
2. alt - Specifies an alternate text for the image

**Background Image on a HTML element**
To add a background image on an HTML element, use the HTML style attribute and the CSS background-image property:

**Example**
Add a background image on a HTML element:

//<div style="background-image: url('img_girl.jpg');">

Practical positioning examples
This article shows how to build some real world examples to illustrate what kinds of things you can do with positioning

 we've got a <section> element with a class of info-box, which contains a <ul> and a <div>. The unordered list contains three list items with links inside, which will become the actual tabs to click on for displaying our content panels. The div contains three <article> elements, which will make up the content panels that correspond to each tab. Each panel contains some sample content.

 //<section class="info-box">
  <ul>
    <li><a href="#" class="active">Tab 1</a></li>
    <li><a href="#">Tab 2</a></li>
    <li><a href="#">Tab 3</a></li>
  </ul>
  <div class="panels">
    <article class="active-panel">
      <h2>The first tab</h2>

      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque turpis nibh, .</p>
    </article>


### Bookmark/Skim
* .You can add comments to your code between the
<!-- and --> markers.
* . The id and class attributes allow you to identify
particular elements.
* .The <div> and <span> elements allow you to group
block-level and inline elements together.
* . <iframes> cut windows into your web pages through
which other pages can be displayed.
* .The <meta> tag allows you to supply all kinds of information about your web page.
* . Escape characters are used to include special
characters in your pages such as <, >, and ©..
