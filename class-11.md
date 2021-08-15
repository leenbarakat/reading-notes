# HTML Images 

Images can improve the design and the appearance of a web page.

HTML Images Syntax
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The img tag is empty, it contains attributes only, and does not have a closing tag.

The img tag has two required attributes:

src - Specifies the path to the image

alt - Specifies an alternate text for the image

**The src Attribute**

The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

**The alt Attribute**

The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image

![p](https://www.crimsondesigns.com/blog/wp-content/uploads/2019/05/html-img-element.gif)

# Image Size - Width and Height

You can use the style attribute to specify the width and height of an image.

![l](https://www.wikihow.com/images/thumb/b/be/Set-Image-Width-and-Height-Using-HTML-Step-3-Version-3.jpg/v4-460px-Set-Image-Width-and-Height-Using-HTML-Step-3-Version-3.jpg.webp)

The width and height attributes always define the width and height of the image in pixels.

## Width and Height, or Style?

The width, height, and style attributes are all valid in HTML.

However, we suggest using the style attribute. It prevents styles sheets from changing the size of images.

![m](https://www.wikitechy.com/css/img/css-images/css-background-image-size.png)

to read more about images in HTML visit [HTML imgs](https://www.w3schools.com/html/html_images.asp)

# HTML audio

The HTML < audio > Element

To play an audio file in HTML, use the < audio > element

HTML Audio - How It Works
The controls attribute adds audio controls, like play, pause, and volume.

The < source > element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.

The text between the < audio > and </ audio > tags will only be displayed in browsers that do not support the < audio > element.


![audio](https://res.cloudinary.com/practicaldev/image/fetch/s--MA5hKls8--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/wh2li7815smb450m1c19.png)

## HTML < audio > Autoplay

To start an audio file automatically, use the autoplay attribute

![m](https://www.wikitechy.com/step-by-step-html-tutorials/attributes/img/attributes-images/code-explanation-autoplay-attribute-in-html.png)

## Browser Support

The numbers in the table specify the first browser version that fully supports the <audio> element

![z](https://cdn-media-1.freecodecamp.org/images/1*pHYI6GbxxHUL5A_FDTdK1A.png)

# HTML video

The HTML < video > element is used to show a video on a web page.

The HTML < video > Element

To show a video in HTML, use the < video > element

![m](https://www.simplilearn.com/ice9/free_resources_article_thumb/html-video-tag.PNG)

How it Works

The controls attribute adds video controls, like play, pause, and volume.

It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

The < source > element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

The text between the < video > and < /video > tags will only be displayed in browsers that do not support the < video > element.

HTML video formats and which browsers support them 

![m](https://cdn-media-1.freecodecamp.org/images/1*pHYI6GbxxHUL5A_FDTdK1A.png)

HTML Video - Methods, Properties, and Events

The HTML DOM defines methods, properties, and events for the < video > element.

This allows you to load, play, and pause videos, as well as setting duration and volume.

There are also DOM events that can notify you when a video begins to play, is paused, etc.

