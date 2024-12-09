# HTML Questions

## What is HTML?

HTML stand for HyperText Markup Language. Hypertext defined the link between web
pages. Markup Languages is used to define the text document withing the tags
that defined the structure of the web page. (HTML is not case sensitive)

## Difference between HTML and XHTML

XHTML stands for Extensible Hypertext Markup Language. It is an extension of
HTML and is stricter and more structured than HTML.

Most important differences from HTML:

- Doctype is mandatory
- The xmls attribute in `<html>` is mandatory
- `<html>`, `<head>`, `<title>` and `<body>` tags are mandatory
- Elements must always be properly nested, closed and in lowercase
- Attributes names must always be in lowercase
- Attributes values must always be quoted
- Attributes minimization is forbidden (
  `<input type="text" disabled="disabled"/>`)

## What are the various markup languages available?

- HTML: Hypertext Markup Language
- KML: Key whole Markup Language (is a file format used to display data in Earth
  browsers such as Google Earth or Google maps. It uses a tag based structure
  with reused elements and attributes and is based on XML standard)
- MathML: Mathematical Markup Language (is used to represent mathematical
  equations or expressions in web browsers like other HTML elements)
- SGML: Standard Generalized Markup Language ( is a specification for defining
  declarative markup languages. Since its fifth edition HTML is no longer SGML
  based and has its own parsing rules)
- XHTML: Extensible Hypertext Markup Language
- XML: Extensible Markup Language (does not do anything, is it information that
  is wrapped in tags, does not use predefined tags like HTML)

  ## What is the difference between HTML and HTML5

* HTML supports audio and video controls with the use of `<audio`> and `<video>`
  tags, no need for Flash player support anymore
* Uses SQL databases and applications cache to store offline data instead of
  cookies
* Allows JavaScript to run in the background (is possible due to JS Web worker
  API in HTML5)
* Vector graphics is additionally an integral part of HTML5 like SVG and canvas
  (no need for extra technologies)
* Allow drag-and-drop effects and support target blank attribute
* More mobile friendly
* The doctype declaration is more simple and shorter
* Has new elements for web page structure like nav, header, footer, etc.
* Is capable of handling inaccurate syntax
* Contains attributes like charset, async and ping

## What is !DOCTYPE?

A doctype or document-type declaration is an instruction that tells browser what
markup language is used in the current page. The doctype is not an element or a
tag, it lets browser know about the version of the markup language that is used
in the document. The Doctype for HTML5 is case insensitive

## What are the elements and tags, and what are the differences between them?

Tags are the starting and ending parts of an HTML element. They begin with "<"
and end with ">" symbols, whatever is inside those elements are cold tags.

Elements is a collection of a start tag, end tag and its attributes, it encloses
the content between the tags.

## What are the various heading tags and their importance?

There are 6 levels of headings defined by HTML, h1 to h6 where h1 has the
highest level and h6 - the lowest

Importance of headings:

- Search Engines use headings for indexing the structure and content of the
  webpage
- Headings are used for highlighting important topics
- They provide valuable information and tell us about the structure of the
  document

## How to redirect to a particular section of a page using HTML?

Anchor tag can be used for this purpose. We need to add "id" attribute to an
element we need to be redirected to and use the same id in href attribute with
"#" in the anchor tag.

# What are attributes?

Attribute is used to provide extra or additional information about the element.
It consists of two parts - name and the value.

## Are `<b`> and `<strong>`,`<i>` and `<em>` tags the same? If not, then why?

The main difference between those 2 tags are that `<strong>`, `<em>` tag had
semantic value while `<b>`/ `<i>` tag is just offset text conventionally styles
in bold.

## What is the use of the target attribute in the `<link>` tag?

It is used to specify the window or a frame where the linked document will be
loaded, it not supported in HTML5 Attribute values:

- \_blank: opens te link in a new window
- \_self: opens the liked document in the same frame
- \_parent: opens the linked document in the parent frameset
- \_top: opens the linked document in the full body of the window
- framename: opens the linked document in the named frame

## What are the HTML tags used to display a table?

- `<table>` is used to define the table
- `<tr>` is used to define a row in a table
- `<th>` is used to define a cell header in the table
- `<td>` is used to define a cell in a table
- `<caption>` defined table caption
- `<colgroup>` defined a group of one or more columns in a table for formatting
- `<col>` is used with `<colgroup>` to specify column properties for each column
- `<tbody>` defines a group of body content in a table
- `<thead>` groups the header content in a table
- `<tfooter>` groups the footer content in a table

## What is the difference between block and inline elements?

A block element always starts with a new line and stretches out to the right and
left as much as it can An inline element does not start on a new line and only
takes up as much width as necessary

## What is the difference between classes and id?

"Id" is unique though the page and can only be applied to one element while
"class" selector can be applied to multiple elements at the same time

## What are the tags that can be used inside the `<head>` tag?

`<head>` element is a like a container for metadata, which is daa that is not
displayed on the page and might have the following elements:

- `<title>` defines the title of the page
- `<link>` is mostly used to link an external CSS file
- `<meta>` is used to specify charset, page description, keywords, author of the
  document nd viewport settings. This information is not displayed on the page
  but is used by the browser and search engines
- `<base>`
- `<style>` is used to make internal CSS within the page
- `<script>` is used to define JS withing the HTML page or to connect external
  JS file

  ## What are semantic elements?

  Semantic elements tel about the type of the content to the browser and the
  developer.

  - **`article`** contains independent content which does not require any other
    context
  - **`section`** separates sections of the content, might contain a subheading
  - **`header`** is used for the header of the section or a page
  - **`main`** defined the main content of the page
  - **`footer`** contains contact information, copyright information, etc.
  - **`nav`** defines navigation links in the form of nav abr or nav menu
  - **`aside`** places content in the sidebar - aside from the main content
  - **`details`** is used for displaying additional details that user can hide
    or view
  - **`figure and captions`** is used to add an image with a small description
  - **`mark`** is used to highlight the text

## What are HTML entities?

HTML entities are reserved characters that are used in the HTML document and are
not present in the standard keyboard. For example "<" or ">" are reserved for
tags

## What is HTML encoding?

Encoding ensures that text is correctly displays in the browser and not
interpreted as HTML. For example in the URL space is replaced with "%20" nad "/"
is replaced by "%2F" since it is a reserved character

## What is the difference between POST and GET methods?

**`GET`** requests data from a specified resource **`POST`** is used to submit
data to be processed to a specific source

## What is HTML canvas?

The HTML "canvas" element is used to draw graphics via JavaScript, it is only a
container for graphics. JavaScript needs to be used to actually draw the
graphics. It has several methods for drawing paths, boxes, circles, text and
adding images

## What is an SVG?

SVG stands for Scalable Vector Graphics and defines vector-based graphics in
XML. SVG graphics do not loose quality idf they are zoomed or resized and every
element and attribute in SVG fle can be animated.

Advantages of using SVG:

- can be created abd edited with any text editor
- can be searched, indexed, scripted and compressed
- are scalable
- can be printed with hight quality in any resolution

## How can we allow the browser to tll the location using HTML Geolocation API?

It uses JavaScript to give the latitude and longitude to the backend server. It
can be created as follows

```
const location = navigator.geolocation
```

## What is HTML Web Storage API?

SessionStorage and LocalStorage are known as the web storage API.

- SessionStorage and LocalStorage are used to store data on the client-side.
- The maximum limit of data saving for both is 5 MB.
- Data in SessionStorage exists while the current tab is open and will be
  automatically erased when it is closed, while data in LocalStorage exists
  until user manually erases it.

## What are form in HTML ?

HTML Form is a document that stores information of a user on a wev server using
interactive controls. It contains different kinds of information like username,
email, password, etc.

The elements used in a form are input, check box, submit button, radio button,
etc.

## What are void elements?

Void elements are elements that do not have a closing tag and do not contain any
content within it. For example, `<br>`, `<hr>`, `<img>`, `<input>`, `<link>`,
`<base>`, `<meta>`, `<param>`, `<area>`, etc.

## How Container tag is different from an Empty tag?

The Container tag generally consist of 3 parts - starting and closing tags and
content. They can also have more tags inside the content.

Empty tags are [Void Elements](What are void elements)

## What tags are used to separate a section of a text?

- `<br>` breaks the current line and conveys the flow to the next line
- `<p>` contains the text in the from of a new paragraph
- `<blockquote>` defines a large quoted section

## What are logical and physical tags?

Logical tags are used to display the text according to the logical styles
Physical tags provide actual physical formatting tot he text.

## How do you serve a page with content in multiple languages?

When an HTTP request is made to a server, the requesting user agent usually
sends information about language preference, such as in the `Accept-Language`
header. The server then can use this information to return a version of the
document in the appropriate language if such alternative is available. The
returned HTML document should declare the `lang` attribute in the `<html>` tag,
such as `<html lang="en">...</html>`

To let the search engine know about the same content available in different
languages, we should use `<link>` tags with the `rel="alternate"` and
`hreflang="..."`. For example,
`<link rel="alternate" hreflang="de" href="http://de.example.com/page.html" />`

## What kind of things to be wary when developing multilingual sites?

1. Search Engine Optimization

- should use `lang` attribute on the `html` tag
- include the locale in the URL (en_US)
- should use `<link>` tags with the `rel="alternate"` and `hreflang="..."`
- use a fallback page for unmatched languages -
  `<link rel="alternate" hreflang="x-default" href="http://fallback-page.html" />`

2. Understanding difference between locale and language - locale setting control
   how numbers, dates and times are displayed for the region.

3. Understanding language differences within a country ot countries:

- en - en_US, en_GB
- zh - zh_CH (Chinese simplified), zh_TW(Chinese traditional)

4. Consider difference in the length of the text in different languages

5. Consider language reading direction

6. Do not concatenate translated strings

7. Formatting dates and currencies

8. Do not put text in the images

9. Be mindful of how colors are perceived

## What are `data-` attributes are good for?

It is used to store extra data within DOM itself, without other non-standard
properties on DOM. is it also used to store information by third-party libraries
or frameworks, like Bootstrap.

It is not very encouraged to use `data-*` attributes due to user's ability to
modify it by using "inspect element" in the browser.

But this attribute is very useful as an identified for end-to-end testing
frameworks, without adding classes or ids just for test which are primarily for
other purposes.

## What are building blocks of HTML5?

- Semantic elements such as the header, main, section, footer, etc.
- Introduced new attributes for the form's tag.

* The local storage of data that allows webpages to function more effectively
  offline.
* Embedding multimedia is possible without third-party plugins.
* DOM and API's.
* Support for math formulas and SVG files.
* Canvas that offers a much greater range of presentation options.

## What is the difference between cookie, session storage and local storage?

**`Local Storage`**:

- data persists even when the browser is closed and reopened. It remains until
  explicitly cleared.
- generally allows for about 5MB of data.
- accessible from any window/tab of the same origin.
- ideal for storing non-sensitive data that needs to persist across sessions,
  like user preference. E.g. `localStorage.setItem('theme', 'dark');`

  **`Session Storage`**:

  - data is stored for the duration opf the page session.Is cleared when the tab
    or window is closed.
  - Similar to local storage, about 5MB.
  - data is only accessible within the same window or tab.
  - suitable for data that should be on;y retained during a single session, like
    data for multi-step form.

    **`Cookies`**:

    - can be set to expire at a specific date or after a certain amount of time.
      Persists across the browser sessions until expires.
    - is limited to 4kb per cookie. sent with every HTTP request tot he server,
      making them suitable for server-side reading.
    - is used for session management, personalization, and tracking. Crucial for
      authentication purposes.

## What is the difference between `<script>`, `<script async>` and `<script defer>`?

`<script>` is the default way of including JavaScript.

The browser blocks HTML parsing while the script is being downloaded and
executed The browser will not continue rendering the page until script has
finished executing

`<script async>` downloads the script asynchronously in parallel with parsing
HTML.

Executes the script as soon as it is loaded, which can lead to interrupting HTML
parsing.

`<script defer>` downloads script in parallel with parsing HTML but is executed
only after HTML is fully parsed.

## What is progressive rendering?

Progressive rendering is rendering a page in such a manner that hight priority
components will be rendered first. Priority of the components depends on the
viewport which means that components that come in the viewport after loading the
website for the first time should get hight priority and components below
viewport should get lower priority.

## How progressive rendering is different from SSR and CSR?

In progressive rendering the web page is divided into different parrs on the
basis of priority. Different parts will be rendered sequentially according to
SSR and sent to the client side - hight priority part of the page is rendered
and sent to the client side, then low priority part of the page is rendered and
sent to the client side.

- it improves the load time of the website, which lead to a better user
  experience.
- it optimizes the critical rendering path (steps that are done between
  receiving HTML, CSS and JS code and converting them into a visual webpage).

Ways to achieve progressive rendering:

1. **`Lazy loading`** of the image - loading an image when it is about to come
   in the viewport instead of loading all images initially at once.

2. **`Not processing all the CSS initially`**

## Why would you use `srcset` attribute in an image tag?

`srcset` attribute is useful for serving different images tot he user depending
on their device display width

`<img srcset="small.jpg 500w, medium.jpg 1000w, large.jpg 2000w" alt="..."/>`

## Have you used different HTML templating languages before?

Template languages are used in most frameworks that are not Javascript. They
dynamically generate HTML when client requests it.

I've used JSX a lot.

## What is the difference between `canvas` and `svg`?

Canvas is raster-based, working with pixels, while SVG is vector-based, using
mathematical descriptions of shapes. Canvas used imperative (повелительное)
drawing, where each step is specified with JavaScript, is ideal for dynamic and
interactive graphics.

SVG uses declarative drawing with shapes and paths defined directly in HTML,
making it more accessible and SEO friendly. Canvas is optimal for complex scenes
due its lower overhead, but scaling may lead to image quality loss. SVG is
resolution independent and adapts to various screen sizes without sacrificing
quality.

Canvas suits dynamic, performance-intensive graphics, while SVG excels in
scalable, resolution-independent graphics, with accessibility and SEO
advantages.
