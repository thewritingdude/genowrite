# Genowrite
*Construction work ahead - distraction-free* by thewritingdude

-----

## Purpose & History

Simply put, I needed a word editor which had

* autocorrect capability
* dark theme
* export and import from file
* word and character counter

I couldn't find any editor that could do all these, so I thought I could make one to fit my needs.
I thought that [Litewrite](http://github.com/litewrite/litewrite) could be the best basis for starting, looking at the code, so I forked it and moved it in the direction I wanted.

### Similarity and differences with Litewrite

* Added autocorrect capability.\
The feature it's there but it's kind of empty. When I'll write I'll add more rules (in Italian).
Note that it's active a rule that no two capitalized characters can be at a beginning of the word. Sorry folks of IJmuiden (:
* Dark theme\
It's a simple change of CSS rules, but it's really a feature that was what I needed. A good choice is to be able to choose between the two.
* Choosing a title for the note\
Through a very duct-tapey box at the bottom left it is possible to change the title of the note.
* Adding export and import of .txt files\
Through the combinations Ctrl+E and Ctrl+I it is possible to export and import a file in .txt format.
Note that the title is imported automagically.
* Word and character counter
A simple word and character counter found in the bottom of the page
* Removed remote sync
I'm sorry but I found the small popup hereditated by Litewrite a little bit distratcing and by the way I'm not planning to use that feature. It will be reinstated when I understand what and how remoteStorage works :)


## TODO

*Note: All of these will be done when they they're done.*
* Select theme.
* Add more autocorrect words and tokens.
* Add a menu at the bottom left with shortcut.
* Correct bugs.
+ Reinstate remoteStorage sync, without borrowing API keys :)
* Implement import/export of .docx files.
* Other stuff that I am forgetting...

------

## Grown boys zone

## Programming language

This editor is written in HTML+CSS+JS, so anyone familiar with this environment should feel at home.

The frameowrk used is [BackboneJS](https://backbonejs.org), but anyone with a grasp of JQuery (like I did when I started working on it) could get his/her hands dirty with it.

### Play with the development environment

Set up your development environment:

1. `git clone https://github.com/thewritingdude/genowrite.git`
2. `cd genowrite`
3. Install [node.js](http://nodejs.org/)
5. Run `npm install` to install the development dependencies
6. `npm start` to start a web server at [http://localhost:8000](http://localhost:8000)
7. Check your code style with `npm run lint`
8. Build the production version with `npm run build`

------

## Thanks 

Forked by [Litewrite](http://github.com/litewrite/litewrite) by [Jan-Christoph Borchardt](http://jancborchardt.net) & [Jorin Vogel](https://jorin.me).\
[Alegreya](http://www.huertatipografica.com.ar/tipografias/alegreya/ejemplos.html) typeface by Juan Pablo del Peral.

## License

Copyleft (c) 2020 [Armando Capozza](http://githug.com/thewritingdude), licensed under the [Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html) version 3 or later. See license.txt for the full license text. Short: **Do anything you want as long as you credit us and redistribute your changes under the same conditions.**
