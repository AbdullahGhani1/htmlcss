<!-- Link A Tag -->
# \<a\></a> Tag

- The \<a\></a> tag defines a hyperlink, which is used to link from one page to another.

### Example
- Create a link to W3Schools.com:
<a href="https://www.w3schools.com/tags/tag_a.asp">Anchor Tag</a>
 ``` 
<a href="https://www.w3schools.com/tags/tag_a.asp">Anchor Tag</a>
```
- The most important attribute of the \<a\></a> element is the **href** attribute, which indicates the link's destination.
- By default, links will appear as follows in all browsers:

- An **unvisited** link is underlined and blue
- A **visited** link is underlined and purple
- An **active** link is underlined and red
-  If the \<a\></a> tag has no href attribute, it is only a placeholder for a hyperlink.
- A linked page is normally displayed in the current browser window, unless you specify another target.
- Use CSS to style links: CSS Links and CSS Buttons.
### Attributes
|   Attribute   |   Value   |   Description   |
|   ---------   |-----------    |   :------:  |             
|   download    |   filename    |   Specifies that the target will be downloaded when a user clicks on the hyperlink    |   
|   href    |   URL    |   	Specifies the URL of the page the link goes to
|   hreflang    |   language_code   |   Specifies the language of the linked document|
|media|	|media_query|	Specifies what media/device the linked document is optimized for|
|ping|	list_of_URLs|	Specifies a space-separated list of URLs to which, when the link is followed, post requests with the body ping will be sent by the browser (in the background). Typically used for tracking.|
|referrerpolicy|	no-referrer<br>no-referrer-when-downgrade<br>origin<br>origin-when-cross-origin<br>same-origin<br>strict-origin-when-cross-origin<br>unsafe-url|Specifies which referrer information to send with the link|
|rel|   alternate<br>author<br>bookmark<br>external<br>helplicense<br>next<br>nofollow<br>noreferrer<br>noopener<br>prev<br>search<br>tag|	Specifies the relationship between the current document and the linked document
|target|_blank_parent<br>_self<br>_top<br>|	Specifies where to open the linked document|
|type|	media_type|	Specifies the media type of the linked document|


- The \<a\></a> tag also supports the Global Attributes in HTML.

Event Attributes
The \<a\></a> tag also supports the <a href="https://www.w3schools.com/tags/ref_eventattributes.asp">Event Attributes in HTML.
</a>

### Example
- How to use an image as a link:
```
<a href="https://www.w3schools.com">
<img border="0" alt="W3Schools" src="logo_w3s.gif" width="100" height="100">
</a>
```
- How to open a link in a new browser window:

```
<a href="https://www.w3schools.com" target="_blank">Visit W3Schools.com!</a>
```
- How to link to an email address:
```
<a href="mailto:someone@example.com">Send email</a>
```
- How to link to a phone number:
```
<a href="tel:+4733378901">+47 333 78 901</a>
```
- How to link to another section on the same page:
```
<a href="#section2">Go to Section 2</a>
```
- How to link to a JavaScript:
```
<a href="javascript:alert('Hello World!');">Execute JavaScript</a>
```

#### Default CSS Settings
- Most browsers will display the \<a\></a> element with the following default values:
```
a:link, a:visited {
  color: (internal value);
  text-decoration: underline;
  cursor: auto;
}

a:link:active, a:visited:active {
  color: (internal value);
}
```