---
title: HTML Questions
layout: layouts/page.njk
permalink: /questions/html-questions/index.html
---

* What does a `doctype` do?
  * Declaration that tells the browser what version of HTML the document is written in, no longer necessary after HTML5 to add DTD (doctype declaration), if none is added its basically HTML5
* How do you serve a page with content in multiple languages?
  * Typically the lang='en' attribute is in the HTML tag, but you can place it anywhere else like body, div, etc.,
  * Also you can put something like the below to serve a different HTML based on browsers prefferd language
    ```
    <link rel="alternate" hreflang="de" href="http://de.example.com/page.html" />
    ```
* What kind of things must you be wary of when designing or developing for multilingual sites?
  * Overflow, which direction languages are read, general layout, the way dates are used in different languages/grammar
* What are `data-` attributes good for?
  * testing without creating meaningless classes or ID attributes
    ```
    data-selector='the-thing'
    ```
* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  * Semantic elements, styling, multimedia sharing, performance, wide device access
* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
  * These are all key-value storage mechanisms on the client side, localStorage is stored forever, sessionStorage expires when tab is closed, cookies have lower memory capacity
* Describe the difference between `<script>`, `<script async>` and `<script defer>`.
  * ```<script>``` blocks HTML parsing until script is fetched and executed
  * ```<script async>``` script is fetched in parallel and doesnt block HTML parsing, executes when finished fetching
  * ```<script defer>``` script is fetched in parallel but waits for HTML to finish parsing to execute
* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  * script tags generally block HTML parsing so should be loaded after HTML for faster page loads, CSS should be loaded initially so the style attributes are applied when HTML is rendering
* What is progressive rendering?
  * rendering techniques to improve perceived load time
  * Lazy loading images - images not loaded all at once, JS renders image when user scrolls to it
  * Prioritizing visible content for quicker page load, defer some CSS/content/scripts
* Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  * So different resolution images are loaded based on the users device width
  ```
  <img srcset="small.jpg 500w, medium.jpg 1000w, large.jpg 2000w" src="..." alt="">
  ```
  * example device with width of 320px and 2x(retina display) would show medium image because 1000px/320px = 3.125, and is closest to 2x
* Have you used different HTML templating languages before?
  * HBS, EJS; are useful for connecting serve side to the frontend
* What is the difference between `canvas` and `svg`?
  * SVG (scalable vector graphics) is a language for describing 2D graphics and is rendered by an SVG viewer, has better scalability, based on vectors and composed of shapes
  * canvas is used to draw graphics via javascript, container for graphics, better performance with small surface or larger number of objects, based on pixels
* What are empty elements in HTML ?
  * elements that cant have children, examples are area, base, br, col, embed, img, input, link, meta
