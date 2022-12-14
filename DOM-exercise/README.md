# DOM-exercise

### Task A, CSS
1. Click on the green 'Code' button and clone the repo

### Task B, [JavaScript HTML DOM](https://www.w3schools.com/js/js_htmldom.asp)
1. Open main-b.js and write your code for  task-b.html
1. Add another `<article>` element to `<main>` by modifying js/main-b.js:
   * The new `<article>` element should containt the same elements as the existing `<article>` element
   * Select `<main>` element with [DOM-methods](https://www.w3schools.com/js/js_htmldom_elements.asp)
   * Use [innerHTML](https://www.w3schools.com/js/js_htmldom_html.asp) property to add the new `<article>` element to `<main>`element.
   * Note that you need to use `+=` operator to add.
   * If you want to make a multiline string for the HTML, you need to use + operator or create a [template string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
   
### Task C, [JavaScript HTML DOM Elements](https://www.w3schools.com/js/js_htmldom_nodes.asp)
1. Open main-c.js and write your code for task-c.html
1. Add another `<article>` element to `<main>`:
   * The new `<article>` element should containt the same elements as the existing `<article>` element
   * Select `<main>` element with [DOM-methods](https://www.w3schools.com/js/js_htmldom_elements.asp)
   * Use DOM methods (createElement, appendChild) to add the new `<article>` element to `<main>` element.
   
### Task D, content from array by [iterating](https://www.w3schools.com/js/js_loop_for.asp)
1. Open task-d.html
1. Add `<article>` elements to `<main>` by iterating picArray with for loop (or [for..of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of) or [forEach](https://www.w3schools.com/jsref/jsref_foreach.asp)).
   * The new `<article>` elements should containt the same elements as the `<article>` element in previous tasks
   1. Select `<main>`element with DOM-methods
   1. Use DOM methods (createElement, appendChild) to add the new `<article>` elements to `<main>`element.
      * title property from the array goes to to `<h2>` and `<img>` element's alt attribute
      * caption property from the array goes to to `<caption>` element
      * filename property from the array goes to to `<img>` element's src attribute
      * description property from the array goes to to `<p>` element 
      
### Task E, content from array by iterating
1. Open task-e.html
1. Add `<article>` elements to `<main>` by iterating picArray with for loop (main-d.js).
   * The new `<article>` elements should containt the same elements as the `<article>` element in previous tasks
   1. Select `<main>`element with DOM-methods
   1. Use innerHTML property to add the new `<article>` elements to `<main>`element. The end result should be the same as in task D.
