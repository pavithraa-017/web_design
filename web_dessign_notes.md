**allow** is like a permission list that tells the browser what features the iframe is allowed to use.

**accelerometer** lets the iframe use motion sensors so it can detect things like device tilting and rotation. **autoplay** lets the video start playing automatically, and **clipboard-write** lets the iframe write data to the user's clipboard.

**encrypted-media** allows the use of encrypted media extensions to protect the video, **gyroscope** grants access to the device's motion and orientation sensors, and **web-share** allows sharing the iframe content through the device's native share dialogs.

**referrerpolicy** is the rule that determines how much detail you share when your page connects to another page.

**allowfullscreen** allows to view the video in full screen


🖼️ ***Images \& Page Information***



**img** is an HTML element used to display an image on a webpage.

**alt** provides alternative text that describes an image. It is shown/read when the image cannot be displayed and helps screen readers understand the image.

**src** specifies the location or URL of the resource that an element should load, such as an image, audio file, video, or script.

**meta** provides information about the webpage that isn't normally displayed on the page, such as its character encoding or description.

**charset** specifies the character encoding used by the webpage. `UTF-8` allows the page to correctly display most characters and symbols.

**link** connects the HTML document to an external resource, commonly a CSS stylesheet.

**rel** describes the relationship between the current HTML document and the resource specified by *href*. For example, *rel="stylesheet"* tells the browser that the linked file is a CSS stylesheet.



🏗️ ***Page Structure***



**body** contains all the content that is displayed on the webpage, such as text, images, buttons, videos, and sections.

**main** contains the main, unique content of a webpage. It helps browsers and assistive technologies identify the primary content.

**section** groups related content together under a particular topic or purpose, usually with a heading.

**div** is a general-purpose container used to group and organize HTML elements. It has no special meaning by itself.

**footer** contains information at the bottom of a page or section, such as copyright information, contact details, or related links.



🔗 ***Links***



**a** (anchor) creates a hyperlink that allows users to navigate to another webpage, file, location, or resource.

**href** specifies the destination that an anchor (`a`) element should navigate to.

**target** specifies where the linked page or resource should open. For example, *\_blank* opens the link in a new browsing context, usually a new tab.



📋 ***Lists***



**ul** creates an unordered list where the items are normally displayed with bullet points.

**ol** creates an ordered list where the items are normally displayed with numbers or letters.

**li** represents an individual item inside an ordered or unordered list.



✍️ ***Text***



**em** indicates that text should have emphasis. Browsers typically display emphasized text in *italics*.

**strong** indicates that text has strong importance. Browsers typically display it in **bold**.



🖼️ ***Figures***



**figure** represents self-contained content, such as an image, diagram, illustration, or code example, that can be moved independently from the surrounding content.

**figcaption** provides a caption or description for the content inside a *figure* element.





🔘 ***Buttons***



**button** creates a clickable button that can be used for actions such as submitting a form, opening something, or triggering JavaScript.

**id** gives an HTML element a unique identifier. It can be used to target the element with CSS or JavaScript and to create links to a specific location on a page.



🎵 ***Audio \& Video***



**audio** embeds an audio file or audio player into a webpage.

**video** embeds a video player into a webpage.

**source** specifies a media file that can be used by an *audio* or *video* element. Multiple *source* elements can be provided so the browser can choose a supported format.

**controls** tells the browser to display built-in media controls such as play, pause, volume, and the progress bar.

**autoplay** tells the browser to automatically begin playing the audio or video when possible.

**loop** makes the audio or video start again automatically after it reaches the end.

**muted** makes the audio or video start with its sound turned off.

**poster** specifies an image that is displayed as the preview/thumbnail of a video before it starts playing.



🖥️ ***iframe***



**iFrame** embeds another webpage or external document inside the current webpage.

**allow** is like a permission list that tells the browser which features the iframe is allowed to use.

**allowfullscreen** allows content inside the iframe to enter fullscreen mode.

**referrerpolicy** is the rule that determines how much referrer information the browser sends when the iframe loads another resource.





💻 ***JavaScript***

**script** is an HTML element used to include or execute JavaScript code on a webpage. It can contain JavaScript directly or use *src* to load an external JavaScript file.



🔤 ***HTML Character References***



**\&amp;** is a character reference that represents the *\&* (ampersand) character in HTML.

**\&lt;** is a character reference that represents the *<* (less-than) character in HTML.



These are useful when you want the browser to *display HTML-special characters as text* instead of interpreting them as HTML.



⭐ ***A few extra important ones***



**DOCTYPE** tells the browser which version/mode of HTML the document is using.*<!DOCTYPE html>* tells the browser to use modern HTML.

**html** is the root element that contains the entire HTML document.

**head** contains information and resources for the webpage that aren't normally displayed as page content.

**title** specifies the title of the webpage shown in the browser tab.

**p** represents a paragraph of text.

**h1-h6** represent headings, with *h1* being the highest-level heading and *h6* the lowest.

**class** assigns one or more elements to a named group so they can be targeted with CSS or JavaScript.

**type** specifies the type or format of something, such as the media format of a *<source>* or the type of a *<script>*.

**name** gives an element a name that can be used by forms, metadata, and other HTML features.

**content** specifies the value associated with a *meta* element's *name* or *http-equiv* attribute.

**width** specifies the width of an element, such as an image or video.

**height** specifies the height of an element, such as an image or video.





