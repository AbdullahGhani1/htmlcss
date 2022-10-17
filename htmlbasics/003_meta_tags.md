# Meta Tag

- The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data.
- <meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
- Metadata will not be displayed on the page, but is machine parsable.
- Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.
- There is a method to let web designers take control over the viewport (the user's visible area of a web page), through the <meta> tag.

### Attributes

| Attribute  |  Value   |   Description |
| ---------- | -------- |:-------------:|
|   charset |   character_set| Specifies the character encoding for the HTML document|
|content| text| Specifies the value associated with the http-equiv or name attribute   |
|   http-equiv  | content-security-policy<br>content-type<br>default-style<br>refresh |    Provides an HTTP header for the information/value of the content attribute   |
|   name    | application-name<br>author<br>description<br>generator<br>keywords<br>viewport| Specifies a name for the metadata|

### <u>Examples</u>

Define keywords for search engines:

```
<meta name="keywords" content="HTML, CSS, JavaScript">
```

Define a description of your web page:

```
<meta name="description" content="Free Web tutorials for HTML and CSS">
```

Define the author of a page:

```
<meta name="author" content="John Doe">
```

Refresh document every 30 seconds:

```
<meta http-equiv="refresh" content="30">
```

Setting the viewport to make your website look good on all devices:

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

#### The Unicode Consortium

- The Unicode Consortium develops the Unicode Standard. Their goal is to replace the existing character sets with its standard Unicode Transformation Format (UTF).
- The Unicode Standard has become a success and is implemented in HTML, XML, Java, JavaScript, E-mail, ASP, PHP, etc. The Unicode standard is also supported in many operating systems and all modern browsers.
- The Unicode Consortium cooperates with the leading standards development organizations, like ISO, W3C, and ECMA.

#### The Unicode Character Sets

- Unicode can be implemented by different character sets. The most commonly used encodings are UTF-8 and UTF-16:
|Character-set | Description|
|---------|:-----------:|
|   UTF-8   |   A character in UTF8 can be from 1 to 4 bytes long. UTF-8 can represent any character in the Unicode standard. UTF-8 is backwards compatible with ASCII. UTF-8 is the preferred encoding for e-mail and web pages    |
|   UTF-16  | 16-bit Unicode Transformation Format is a variable-length character encoding for Unicode, capable of encoding the entire Unicode repertoire. UTF-16 is used in major operating systems and environments, like Microsoft Windows, Java and .NET.   |

- The first 128 characters of Unicode (which correspond one-to-one with ASCII) are encoded using a single octet with the same binary value as ASCII, making valid ASCII text valid UTF-8-encoded Unicode as well.

- HTML 4 supports UTF-8. HTML 5 supports both UTF-8 and UTF-16!

#### The HTML5 Standard: Unicode UTF-8

- Because the character sets in ISO-8859 were limited in size, and not compatible in multilingual environments, the Unicode Consortium developed the Unicode Standard.
- The Unicode Standard covers (almost) all the characters, punctuations, and symbols in the world.
- Unicode enables processing, storage, and transport of text independent of platform and language.
- The default character encoding in HTML-5 is UTF-8.
- If an HTML5 web page uses a different character set than UTF-8, it should be specified in the <meta> tag like:

#### Example

```html
<meta charset="ISO-8859-1">
```

- The Difference Between Unicode and UTF-8
- Unicode is a character set. UTF-8 is encoding.

```
<meta charset="UTF-8">
```

- Unicode is a list of characters with unique decimal numbers (code points). A = 65, B = 66, C = 67, ....

- This list of decimal numbers represent the string "hello": 104 101 108 108 111

- Encoding is how these numbers are translated into binary numbers to be stored in a computer:

- UTF-8 encoding will store "hello" like this (binary): 01101000 01100101 01101100 01101100  01101111

- Encoding translates numbers into binary. Character sets translates characters to numbers.

### What is The Viewport?

1. The viewport is the user's visible area of a web page.
1. The viewport varies with the device, and will be smaller on a mobile phone than on a computer screen.
1.Before tablets and mobile phones, web pages were designed only for computer screens, and it was common for web pages to have a static design and a fixed size.
1.Then, when we started surfing the internet using tablets and mobile phones, fixed size web pages were too large to fit the viewport. To fix this, browsers on those devices scaled down the entire web page to fit the screen.

This was not perfect!! But a quick fix.

#### Setting The Viewport

- HTML5 introduced a method to let web designers take control over the viewport, through the <meta> tag.

- You should include the following ```<meta>``` viewport element in all your web pages:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

- This gives the browser instructions on how to control the page's dimensions and scaling.

- The **width=device-width** part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

- The **initial-scale=1.0** part sets the initial zoom level when the page is first loaded by the browser.

```html
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```
