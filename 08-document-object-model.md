# READ ME
## Document Object Model

The following exercises will give you practice using the Document Object Model.

Copy the files in `08-document-object-model`. You will need to create a file, `dom.js` for Tasks 1-3 of this exercise. You can view the results in `index.html`. For Task 4, write your script in `cities.js`. You can view the results in `cities.html`.

You must create the elements, attributes and text nodes using only JavaScript. Do not write the elements in HTML! (That would be cheating!)

The methods you use to get an element will determine what you need to call in order to modify it. (Remember: Some methods return an object; Others return an array!)


## Task 1

In `index.html` is a very basic HTML document structure. The head is missing a `meta` tag (which sets the character set) and a `title` tag.

Add these by creating the elements using DOM methods. The character set for the `meta` tag is "UTF-8"; the page title should be "Working with the DOM".


## Task 2

Add the following to the `body` of `index.html` using DOM methods:

- h1: "Working with the DOM"
- p: "This is so much fun!"


## Task 3

Add the following unordered list to `index.html`:

- ul:
    - li: "HTML"
    - li: "CSS"
    - li: "JavaScript"

Instead of writing methods for each list item write a function which, when called inside a loop, will iterate over an array, build and append each list item to the unordered list.


## Task 4

In `cities.js` is an array of objects. This array is an A-to-Z list of cities around the world. Each country has the following properties: city, country, continent.

Write a loop/function (similar to what you wrote in Task 3) which processes each item in the array. The city name and country should be displayed on the web page as a list item in an unordered list; each city's country is the value of its `id` attribute; each city's continent should be its `class` value.

If the exercise is done correctly, the style sheet added to `cities.html` should be quite colorful! :)

Believe it or not, this can be accomplished with about 15 lines of code!

**Extra Challenge** (if you are up for it!)

When writing HTML, it is best to:

  - avoid spaces within id values
  - write all attributes as lowercase

What methods could you add to standardize country and continent information to transform spaces into hyphens and convert them to lowercase? For example: "North America" to "north-america"
