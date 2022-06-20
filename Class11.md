#Readings: Audio, Video, Images

# Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.*we started to have bandwidth fast enough to support any kind of video (video files are much larger than text or even images.) In the early days, native web technologies such as HTML didn't have the ability to embed video and audio on the Web, so proprietary (or plugin-based) technologies like Flash — and later, Silverlight (both of which are now obsolete) — became popular for handling such content*

Describe the use of the src and controls attributes in the <video> element.*The <video> element allows you to embed a video very easily,the src (source) attribute contains a path to the video you want to embed.*

Why is it important to have fallback content inside the <video> element?*this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers*

Write a very short story where <audio> and <video> are characters.

<video controls>
    <source src="josiahGraduation.webm"
 type="video/webm">
    <source src=" example.mp4"
type="video/mp4">
    <track kind="caption"
    src="subtitles_es.vtt" srclang="es" 
    label="English">
    <p>Josiah is graduated from daycare. He will be attending pre K this fall now that he is four years of age.</p> 
 </video>   

# A complete Guide To Grid

1.  How does Grid layout differ from Flex?
*grid – generates a block-level grid*

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
grid containers establishes a new grid formatting context for its contents.
grid item is the line where the item begins,is the line where the item ends.


# Responsive Images
1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?*This helps to improve performance across different devices*

2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.
*srcset* One or more strings separated by commas, indicating possible image sources for the user agent to use. 
**Each string is composed of:**
1. A URL to an image
2.  Optionally, whitespace followed by one of:
    - A width descriptor (a positive integer directly followed by w). The width descriptor is divided by the source size given in the sizes attribute to calculate the effective pixel density.
    - A pixel density descriptor (a positive floating point number directly followed by x).

*sizes* One or more strings separated by commas, indicating a set of source sizes  
1. A media condition. This must be omitted for the last item in the list.
2. A source size value.

3. How is srcset more helpful for responsive images than CSS or JavaScript? *solve the problems by letting you offer the browser several image files, either all showing the same thing but containing different numbers of pixels (resolution switching), or different images suitable for different space allocations (art direction).*


# HTML Images

+ In order to put a simple image on a webpage, we use the <img> element. The src attribute contains a path pointing to the image you want to embed in the page, which can be a relative or absolute URL, in the same way as href attribute values in <a> elements.

+ alt. Its value is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of a slow internet connection.

+ the width and height attributes to specify the width and height of your image.


# Other Embedded Technologies

1. <iframe>s are for embedding other web pages, and the other two allow you to embed PDFs, SVG, and even Flash — a technology that is on the way out, but which you'll still see semi-regularly

2. The <object> HTML element represents an external resource, which can be treated as an image, a nested browsing context, or a resource to be handled by a plugin.

3. The <embed> HTML element embeds external content at the specified point in the document. This content is provided by an external application or other source of interactive content such as a browser plug-in.



## Things I want to know more about










