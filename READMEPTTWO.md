JULY 30, 2021
/
[#HTML5](https://www.freecodecamp.org/news/tag/html5/)
# Basic HTML5 Template: Use This HTML Boilerplate as a Starter for Any Web Dev Project

Jessica Wilkins

![Coding Office](https://plus.unsplash.com/premium_photo-1661331911412-330f2e99cf53?q=80&w=1170&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

When you are building a new website, it is important to have a good starting foundation. In this article, I will explain what an HTML 5 boilerplate is and how to create a basic template to use in your projects.

### What is an HTML 5 boilerplate?
According to [Wikipedia](https://en.wikipedia.org/wiki/Boilerplate_code#HTML),

> **boilerplate code** or just **boilerplate** are sections of code that are repeated in multiple places with little to no variation.
A boilerplate in HTML is a template you will add at the start of your project. You should add this boilerplate to all of your HTML pages.

### Example of HTML 5 boilerplate
Let's take a look at a basic example.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
	<script src="index.js"></script>
  </body>
</html>
```
### What is a doctype in HTML?
The first line in your HTML code should be the doctype declaration. A doctype tells the browser what version of HTML the page is written in.
```html
<!DOCTYPE html>
```
If you forget to include this line of code in your file, then some of the HTML 5 tags like `<article>`, `< footer >`, and `<header>`  may not be supported by the browser.

### What is the HTML root element?
The `<html>` tag is the top level element of the HTML file. You will nest the `<head>` and `<body>` tags inside of it.

```html
<!DOCTYPE html>
<html lang="en">
  <head></head>
  <body></body>
</html>
```
The `lang` attribute inside the opening `<html>` tag sets the language for the page. It is also good to include it for accessibility reasons, because screen readers will know how to properly pronounce the text.

### What are head tags in HTML?
The `<head>` tags contain information that is processed by machines. Inside the `<head>` tags, you will nest metadata which is data that describes the document to the machine.

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
</head>
```
### What is UTF-8 character encoding?
UTF-8 is the standard character encoding you should use in your web pages. This will usually be the first `<meta>` tag shown in the `<head>` element.

 ```html
 <meta charset="UTF-8">
 ```
According to the [World Wide Web Consortium](https://www.w3.org/International/questions/qa-choosing-encodings),

> A Unicode-based encoding such as UTF-8 can support many languages and can accommodate pages and forms in any mixture of those languages. Its use also eliminates the need for server-side logic to individually determine the character encoding for each page served or each incoming form submission.

### What is the viewport meta tag in HTML?
This tag renders the width of the page to the width of the device's screen size. If you have a mobile device that is 600px wide, then the browser window will also be 600px wide.

The initial-scale controls the zoom level. The value of 1 for the initial-scale prevents the default zoom by browsers.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
### What does X-UA-Compatible mean?
This `<meta>` tag specifies the document mode for Internet Explorer. `IE=edge` is the highest supported mode.
```html
<meta http-equiv="X-UA-Compatible" content="ie=edge">
```
### What are HTML title tags?
The `<title>` tag is the title for the web page. This text is shown in the browser's title bar.
```html
<title>HTML 5 Boilerplate</title>
Screen-Shot-2021-07-30-at-4.15.25-AM
```
### CSS stylesheet
This code will link your custom CSS to the HTML page.  `rel="stylesheet"` defines the relationship between the HTML file and the external stylesheet.  
```html
<link rel="stylesheet" href="style.css">
```
### Script tags in HTML
External script tags will be placed just before the ending body tag. This is where you can link your external JavaScript code.
```html
<script src="index.js"></script>
```
## Conclusion
You should add an HTML 5 boilerplate to each of your HTML pages. This starter code contains important information like the doctype, metadata, external stylesheets and script tags.

##### References
1. Jessic Wilkins: [Basic HTML5 Template: Use This HTML Boilerplate as a Starter for Any Web Dev Project](https://unsplash.com/photos/programmer-and-ux-ui-designer-working-in-a-software-development-and-coding-technologies-mobile-and-website-design-and-programing-development-technology-CjkMRKROMKQ)