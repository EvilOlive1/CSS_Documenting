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

