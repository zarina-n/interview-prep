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
- The xmls attribute in <html> is mandatory
- <html>, <head>, <title> and <body> tags are mandatory
- Elements must always be properly nested, closed and in lowercase
- Attributes names must always be in lowercase
- Attributes values must always be quoted
- Attributes minimization is forbidden (
  <input type="text" disabled="disabled"/>)

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

* HTML supports audio and video controls with the use of <audio> and <video>
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

## Are <b> and <strong>, <i> and <em> tags the same? If not, then why?

The main difference between those 2 tags are that <strong>, <em> tag had
semantic value while <b>/ <i> tag is just offset text conventionally styles in
bold.

## What is the use of the target attribute in the <lint> tag?

It is used to specify the window or a frame where the linked document will be
loaded, it not supported in HTML5 Attribute values:

- \_blank: opens te link in a new window
- \_self: opens the liked document in the same frame
- \_parent: opens the linked document in the parent frameset
- \_top: opens the linked document in the full body of the window
- framename: opens the linked document in the named frame

## What are the HTML tags used to display a table?

- <table> is used to define the table
- <tr> is used to define a row in a table
- <th> is used to define a cell header in the table
- <td> is used to define a cell in a table
- <caption> defined table caption
- <colgroup> defined a group of one or more columns in a table for formatting
- <col> is used with <colgroup> to specify column properties for each column
- <tbody> defines a group of body content in a table
- <thead> groups the header content in a table
- <tfooter> groups the footer content in a table

## What is the difference between block and inline elements?

A block element always starts with a new line and stretches out to the right and
left as much as it can An inline element does not start on a new line and only
takes up as much width as necessary

## What is the difference between classes and id?

"Id" is unique though the page and can only be applied to one element while
"class" selector can be applied to multiple elements at the same time

## What are the tags that can be used inside the <head> tag?

<head> element is a like a container for metadata, which is daa that is not displayed on the page and might have the following elements:

- <title> defines the title of the page
- <link> is mostly used to link an external CSS file
- <meta> is used to specify charset, page description, keywords, author of the document nd viewport settings. This information is not displayed on the page but is used by the browser and search engines
- <base>
- <style> is used to make internal CSS within the page
- <script/> is used to define JS withing the HTML page or to connect external JS
  file
