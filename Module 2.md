# Module 2

## Module 2.1 : Languages that make up the web

HTML = Hypertext Markup Language

CSS = Cascading Style Sheets

- Responsible for visuals
- Changing the color of the text to controlling the layout

Javascript = Interactivity

- Opening menus, popups, handling dynamic content, etc

These are what makes a website

## Module 2.2 : Intro to HTML

<> = Tags needed to do HTML

`<"Opening Tag">Content<"Closing Tag"/>`

- This is considered to be one element

Semantic HTML = using elements which have semantic meaning

- `<p>` = telling browser its a 'paragraph'

HTML is a markup language (marking up a page)

## Module 2.3 : The root folder and our first HTML file

`my-first-project` = root folder/root directory

`index.html` = first file for the project

Its called index because its what servers automatically go

## Module 2.4 : The doctype, head and body

`<html>` is the root of the document or "root element"

`<head>` is the hidden part of file

Provide extra info about the document

- Author
- Description of the page
- Date the document was published
- ISO
- Shutterspeed

Search engines will see this information

`<body>` is where visitors can see the page

XHTML is XML language and its another markup language

`<!DOCTYPE html>` tells the browser that its an HTML5 doc

Fortunately, HTML5 is the final version

## Module 2.5 : Opening our site in the browser

`ctrl + s` or `cmd + s` to save the file

## Module 2.6 : Headings and Paragraphs

To denote the hierarchy of the website, we use heading levels

IMPORTANT: You can only have one h1 per page (Should)

There is h2 to h6 (No h7 or higher)

Formatting:

- h1 = HTML is awesome!
  - h2 = What is HTML?
  - h2 = Basic page structure
    - h3 = The doctype
    - h3 = The head
    - h3 = The body
  - h2 = Marking up your content
    - h3 = Headings
    - h3 = Paragraphs
    - h3 = Lists

## Module 2.7 : Nesting

`<html>` contains `<head>` and `<body>`

`<head>` contains `<title>`

`<body>` contains `<h1>`, `<h2>`, `<p>`, etc

<body>
  <header>
    <h1>Welcome to TechKnows</h1>
    <p>Your one-stop destination for all things tech.</p>
  </header>
  <main>
    <section>
      <h2>About Us</h2>
      <p>We are a team of passionate tech enthusiasts.</p>
      <p>Our mission is to provide the latest tech news and reviews.</p>
    </section>
    <section>
      <h2>Services</h2>
      <p>We offer a wide range of tech-related services.</p>
      <p>From consulting to product reviews, we've got you covered.</p>
    </section>
  </main>
  <footer>
    <p>© 2025 TechKnows. All rights reserved.</p>
  </footer>
<body>

`<body>` is the parent of `<header>`, `<main>`, and `<footer>`

Those 3 are siblings to each other

## Module 2.8 : Lists

3 different lists in HTML:

- Ordered lists
- Unordered lists
- Description lists

### Ordered Lists

Numbered list is used with `<ol>`

### Unordered Lists

Unordered list is used with `<ul>`

### Description Lists

Description list is used with `<li>`

```html
<ol>
  <li>Item one</li>
  <li>Item two</li>
  <li>Item two</li>
</ol>
<ul>
  <li>Item one</li>
  <li>Item two</li>
  <li>Item two</li>
</ul>
```

## Module 2.9 : Organizing our content with semantic elements

```html
<body>
  <header>
    <!-- logo + navigation -->
  </header>
  
  <main>
    <!-- the majority of the content -->
    <section> <!-- a section of content --> </section>
    <section> <!-- another section of content --> </section>
    <section> <!-- yet another --> </section>
  </main>
  
  <footer>
    <!-- copyright, sometimes another nav
         social links, contact, etc. -->
  </footer>
</body>
```

## Module 2.10 : Comments

```html
<!--This is a comment-->
```

## Module 2.11 : Strong and Emphasis

`<strong>` strong importance (Bold)
`<em>` emphasis (Italics)

## Module 2.12 : Black and Inline elements

`<section>` are block elements and they stack on top of each other
`<p>` are inline elements and they auto create new line

## Module 2.13 : Creating the second page

Lower case is better for file names

hyphens are better than spaces for file names

## Module 2.14 : Links and Attributes

`<a>` is an inline element

### Relative Links

`href` links the two pages together
href = Hypertext Reference
`<a href="#"></a>` where # is a placeholder

### Absolute Links

`<a href="https://www.reddit.com/"></a>`  is absolute

Having https or http makes it absolute

## Module 2.15 : Link Text

The text we include inside of our links must be descriptive of where the link is going

The text inside the link should tell people everything they need to know about where that link goes

## Module 2.16 : Images

`src` = the source
`alt` = alternative text

### Source

Bad practice : Using absolute paths
Good practice : Using unsplash.com or pexels.com

### Alternative Text

2 main purposes:

- The browser will show that text if the image fails to load

- Used by assistive technologies like screen readers

### File types

Recommended types : .jpg and .png

### Image weights

Aim to be under 100kb

## Module 2.17 : The only tags you need to know (for now)

### The behind the scenes tags

`<!DOCTYPE html>` - Tells the browser it is an HTML document, using the most recent version of HTML.

`<html>` - Creates the "root" of the document. Everything other than the <!DOCTYPE html> goes inside of the `<html> </html>` tags.

`<head>` - Contains extra information for the browser that doesn't appear on the page itself.

`<title>` - The title of your page. The title of the page, which will appear in the browser tab and in search results.

`<style>` and `<link>` - Used for adding CSS to your page. The `<style>` allows you to write CSS directly within that HTML file, while the `<link>` is used to link to a separate (external) CSS file, using an href attribute to point to the CSS file.

`<body>` - Any content inside the body is the content that will be on the page for visitors to see.

### Content/Text related

`<h1> → <h6>` - Heading levels. These create hierarchy within your page. Think of them as creating a table of contents.

`<p>` - Paragraph

`<strong>` - Strong importance (bold by default). This is an inline element.

`<em>` - Emphasis (italic by default). This is an inline element.

`<a>` - Anchor. Used to create links (think of it as anchoring to another location). This is an inline element.

`<ul>` and `<ol>` - Unordered and Ordered lists.

`<li>` - List item. Used inside of `<ul>` and `<ol>` elements.

`<span>` - Similar to `<strong>` and `<em>`, but with no default styling or semantic meaning. Use CSS to style it how you want.

`<img>` - Image. Must have an alt attribute, which describes the image.

### Layout related

`<header>` - Denotes a heading within the document. Often used for the logo and navigation area on a page, but can also be used within other elements (such as an article), to denote the heading for that section of content.

`<main>` - The main content of your page (only one per page).

`<footer>` - Denotes a footer within a document. Like `<header>`, it is often used as the primary footer for an entire page, but you can have footers within other elements as well.

`<nav>` - Used for major navigational elements (not all links, or lists of links must be in a nav).

`<article>` - A piece of content on your page that can stand on it's own.

`<section>` - A section of content.

`<div>` - A division (or box) - no semantic meaning. These are used to organize your content, generally so you can create layouts with CSS.