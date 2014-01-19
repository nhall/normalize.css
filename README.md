# normalize.css

This is a Sass port of the wonderful [Normalize.css] (http://necolas.github.io/normalize.css/) from Nicolas Gallagher.

	Normalize.css is a customizable CSS file that makes browsers render all elements more consistently and in line with modern standards.

	The project relies on researching the differences between default browser styles in order to precisely target only the styles that need or benefit from normalizing.

[Check out the demo](http://necolas.github.io/normalize.css/latest/test.html)

## What does it do?

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Explains what code does using detailed comments.

## How to use it

The Normalize.css has been repurposed as a Sass partial. No other styles should come before Normalize.css. That means `_normalize.scss` should be the first partial imported in your project.

## Browser support

* Google Chrome
* Mozilla Firefox 4+
* Apple Safari 5+
* Opera 12+
* Internet Explorer 8+

## Acknowledgements

Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).
