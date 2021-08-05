# HTML Images

## HTML Images Syntax

The HTML img tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The img
tag creates a holding space for the referenced image.

The img tag is empty, it contains attributes only, and does not have a closing tag.

The img tag has two required attributes:

src - Specifies the path to the image

alt - Specifies an alternate text for the image

How to insert an image in HTML code 

![img](https://www.wikihow.com/images/thumb/d/dc/Insert-Images-with-HTML-Step-5-Version-5.jpg/v4-460px-Insert-Images-with-HTML-Step-5-Version-5.jpg)

**The src Attribute**

The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

**The alt Attribute**

The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image

**Image Size - Width and Height**

You can use the style attribute to specify the width and height of an image.

![img](https://www.wikihow.com/images/thumb/0/00/Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg/v4-460px-Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg.webp)

The width and height attributes always define the width and height of the image in pixels.

To read more about images in HTML visit [HTML img](https://www.w3schools.com/html/html_images.asp)

# Colors in CSS 

CSS Color property is used to set the color of HTML elements. This property is used to set font color, background color etc.

Color of an element can be defined in the following ways:

- Built-In Color

- RGB Format

- RGBA Format

- Hexadecimal Notation

- HSL

- HSLA

**Built-In Color:** These are a set of predefined colors which are used by its name. For example: red, blue, green etc.

**RGB Format:** The RGB(Red, Green, Blue) format is used to define the color of an HTML element by specifying the R, G, B values range between 0 to 255. For example: RGB value of Red color is (255, 0, 0), Green color is (0, 255, 0), Blue color is (0, 0, 255) etc.

**RGBA Format:** The RGBA format is similar to the RGB, but the difference is RGBA contains A (Alpha) which specify the transparency of elements. The value of alpha lies between 0.0 to 1.0 where 0.0. represents fully transparent and 1.0 represents not transparent.

**Hexadecimal Notation:** The hexadecimal notation begins with # symbol followed by 6 characters each range from 0 to F. For example: Red #FF0000, Green #00FF00, Blue #0000FF etc.

**HSL**: HSL stands for Hue, Saturation, and Lightness respectively. This format uses the cylindrical coordinate system.

- Hue: Hue is the degree of the color wheel. Its value lies between 0 to 360 where 0 represents red, 120 represents green and 240 represents blue color.

- Saturation: It takes percentage value, where 100% represents completely saturated, while 0% represents completely unsaturated (gray).

- Lightness: It takes percentage value, where 100% represents white, while 0% represents black.

**HSLA:** The HSLA color property is similar to HSL property, but the difference is HSLA contains A (Alpha) which specify the transparency of elements. The value of alpha lies between 0.0 to 1.0 where 0.0. represents fully transparent and 1.0 represents not transparent.

**Text Color:** It is used to set the color of the text.

**Background Color:** It is used to set the background color of an HTML element.

**Border Color:** It is used to set the border color of an element. Border-style is used to set the border type.

**List of Colors:** Following are the list of few CSS colors.

![c](https://blog.hubspot.com/hs-fs/hubfs/Google%20Drive%20Integration/Draft%20-%20CSS%20Colors-4.png?width=600&name=Draft%20-%20CSS%20Colors-4.png)

# HTML text 

**HTML Formatting Elements**

Formatting elements were designed to display special types of text:

b - Bold text

strong - Important text

i - Italic text

em - Emphasized text

mark - Marked text

small - Smaller text

del - Deleted text

ins - Inserted text

sub - Subscript text

sup - Superscript text

To know more about texts visit [HTML text](https://www.w3schools.com/html/html_formatting.asp)

# JPG vs PNG vs GIF 

The three most popular image formats for the web are JPG, GIF, and PNG. These formats represent very different approaches to the problem of delivering an image with minimum file size anddownload time. This page describes the difference between these approaches and offers tips on when to use each.

While GIF is great for computer generated images with limited palettes, JPG is far better for photographs. It gives better quality images for the same file size. Below is a comparison. The image on the left is a blowup of a very small region of a large image compressed with JPG. The image on the right is the same region compressed using GIF. The GIF file is 2.4 times bigger than the JPG, but is clearly of lower quality. Note the use of pixel dithering to try to match the color gradations in the shirt. (You may want to back up from your monitor for a more realistic comparison of the appearance of the images.)

![m](https://matthews.sites.wfu.edu/misc/jpg_vs_gif/PngTest/JpgVsGif_srgb.png)

 

For an even more extreme example, here is a comparison between a more highly compressed JPG and the same GIF. In this image below, the file size of the JPG on the left is 18 times smaller than that of the GIF on the right.

![om](https://matthews.sites.wfu.edu/misc/jpg_vs_gif/PngTest/JpgVsGif2_srgb.png)

## When to use GIF?

Use GIF when there are large areas of uniform color and the total number of colors is smaller than 256. Consider the following image:

![l](https://matthews.sites.wfu.edu/misc/jpg_vs_gif/PngTest/testImage_srgb.png)

This above original image is saved in the PNG lossless format.

Next, the image was saved as a GIF and as a JPG:

![ls](https://matthews.sites.wfu.edu/misc/jpg_vs_gif/testImage.gif) 
GIF, 1.448 K

![a](https://matthews.sites.wfu.edu/misc/jpg_vs_gif/testImage.jpg) JPG, 2.436 K

The GIF image is a flawless copy of the original. GIF can make flawless copy at high compression as long as the image contains large areas of uniform color, as long as the image has no more than 256 colors.

The JPG image above is seriously degraded. The color of the circle has changed, and there are mottled areas in the (supposedly) white areas around the circle and the letters

lease note that the degradation of JPG images is controllable. JPG allows the user to choose the balance between file size and image quality, and one could choose better quality than in the above example. However, doing so results in an even larger file size for the JPG.

In the above case, GIF provides a better, in fact perfect, rendition of the original, while delivering a smaller file size. For images like the above, always use GIF.

## PNG 

As all recent browsers now support the PNG format, it is time to abandon GIF for most purposes. The PNG of the above image is smaller than the GIF, and PNG is not limited to 256 colors as is GIF.

The only reasons to use GIF are for either images with transparency or when you are animating images. PNG has superior transparency.
