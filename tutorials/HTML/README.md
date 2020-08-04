# Master-HTML Learn HTML



This is to learn HTML ::::
==========================

The file can be saved as either .htm or .html as file extension. There is no difference, it is up to you.


The <!DOCTYPE html> declaration defines this document to be HTML5. The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly. It must only appear once, at the top of the page (before any HTML tags). The <!DOCTYPE> declaration is not case sensitive.



The <html> element is the root element of an HTML page

The <head> element contains meta information about the document

The <title> element specifies a title for the document

The <body> element contains the visible page content


<html>
	 <head>
		<title>
			Page Title
		</title>
	 </head>
	 <body>
		<p></p>
	</body>
</html>


Note: Only the content inside the <body> section (the white area above) is displayed in a browser.


HTML Headings:
===============
HTML headings are defined with the <h1> to <h6> tags.
<h1> defines the most important heading. <h6> defines the least important heading


Attributes are used to provide additional information about HTML elements.

==> HTML elements with no content are called empty elements. Empty elements do not have an end tag, such as the <br> element (which indicates a line break). Empty elements can be "closed" in the opening tag like this: <br />.

===> HTML Is Not Case Sensitive : <P> means the same as <p>.
The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.

<img src="img_girl.jpg" width="500" height="600">

===> The width and height are specified in pixels by default; so width="500" means 500 pixels wide.

Lang attribute:
=================
The language of the document can be declared in the <html> tag. 
The language is declared with the lang attribute. Declaring a language is important for accessibility applications (screen readers) and search engines.
The first two letters specify the language (en). If there is a dialect, add two more letters (US).

Single or Double Quotes?
==============================
Double quotes around attribute values are the most common in HTML, but single quotes can also be used.

In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:

Example: 

<p title='John "ShotGun" Nelson'>
Or vice versa:
<p title="John 'ShotGun' Nelson">

HTML Global Attributes:
========================
HTML attributes give elements meaning and context.
The global attributes below can be used on any HTML element.

for example lang attribute which is for every tag.

few more glboal attributes are id, title, lang, style, hidden, translate ...etc

Global Event Attributes:
==========================
HTML has the ability to let events trigger actions in a browser, like starting a JavaScript when a user clicks on an element.

For example onload, onunload attributes..etc


URL Encoding (Percent Encoding):
=====================================
URLs can only be sent over the Internet using the ASCII character-set.

Since URLs often contain characters outside the ASCII set, the URL has to be converted into a valid ASCII format.

URL encoding replaces unsafe ASCII characters with a "%" followed by two hexadecimal digits.
URLs cannot contain spaces. URL encoding normally replaces a space with a plus (+) sign or with %20.

In JavaScript you can use the encodeURIComponent() function to URL encoding.


ISO Language codes:
=====================
==> The HTML lang attribute can be used to declare the language of a Web page or a portion of a Web page. This is meant to assist search engines and browsers. 
==> According to the W3C recommendation you should declare the primary language for each Web page with the lang attribute inside the <html> tag, like this:

ISO Country Codes:
======================
In HTML they can be used as an addition to the language value in the lang attribute.

The first two characters of a language code defines the language. (see previous reference)

The last two defines the country.

Example : lang="en-US"


==> Tip: The default font size is usually 16px.


==> It is best practice to use relative file paths (if possible).

==> Note: Always specify the width and height of an image. If width and height are not specified, the page might flicker while the image loads.

===> Tip: The id and class attributes can be used on any HTML element. And, The id value and class name are case-sensitive.

==> Difference between class and Id attribute is -> An HTML element can only have one unique id that belongs to that single element, while a class name can be used by multiple elements:


The HTML <meta> Element:
==========================
The <meta> element is used to specify which character set is used, page description, keywords, author, and other metadata.

Metadata is used by browsers (how to display content), by search engines (keywords), and other web services.

Setting The Viewport: To VIEW better on different devices
=============================================================

In HTML, there is a method to let web designers take control over the viewport, through the <meta> tag.

The viewport is the user's visible area of a web page. It varies with the device, and will be smaller on a mobile phone than on a computer screen.

You should include the following <meta> viewport element in all your web pages:

<meta name="viewport" content="width=device-width, initial-scale=1.0">
A <meta> viewport element gives the browser instructions on how to control the page's dimensions and scaling.


The HTML <script> Element:
==============================
The <script> element is used to define client-side JavaScripts.
The <script> element either contains script statements, or it points to an external script file through the src attribute.

Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content.

To select an HTML element, JavaScript most often uses the document.getElementById() method.









































