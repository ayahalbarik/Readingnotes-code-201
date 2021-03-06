# HTML Images
Images can improve the design and the appearance of a web page.The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
by the <img src="link"></img>
for example:
<img src="pic_trulli.jpg" alt="Italian Trulli">


## color
With CSS, colors can be specified in different ways:

By color names
**As RGB values**:
An RGB color value is specified with: rgb( RED , GREEN , BLUE ).

Each parameter defines the intensity of the color as an integer between 0 and 255.

For example, rgb(0,0,255) is rendered as blue, because the blue parameter is set to its highest value (255) and the others are set to 0.
**As hexadecimal values**
Hexadecimal color values are also supported in all browsers.

A hexadecimal color is specified with: #RRGGBB.

RR (red), GG (green) and BB (blue) are hexadecimal integers between 00 and FF specifying the intensity of the color.

For example, #0000FF is displayed as blue, because the blue component is set to its highest value (FF) and the others are set to 00
### The properties that allow you to control
the appearance of text can be split into
two groups:
● Those that directly affect the font and its appearance
(including the typeface, whether it is regular, bold or italic,
and the size of the text)
● Those that would have the same effect on text no matter
what font you were using (including the color of text and
the spacing between words and letters)
The formatting of your text can have a significant effect
on how readable your pages are. As we look through these
properties I will also give you some design tips on how to
display your type.

>You can also control the borders, margin and padding
for each box with CSS.


#### JPEG vs PNG vs GIF — which image format to use and when?

The three most commonly used image formats in websites and mobile applications — JPEG, PNG and GIF,Almost all forms of data that we see on the internet — text, image, video etc. — are compressed to reduce the size of data and ensure faster transmission. Choosing the correct format and compression is a major factor that determines image size.
1. **JPEG** is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality.
2. **PNG** is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image
3. **GIF** is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing