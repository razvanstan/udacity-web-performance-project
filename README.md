## Website Performance Optimization portfolio project

Project can be opened by running locally index.html in your browser, 
or can be checked here: https://razvanstan.github.io/udacity-web-performance-project/


#### What was changed: 

HTML: 
- move scripts on footer and set async attribute on them
- move font loading on footer
- move some inline styles to css classes
- on index.html move css from external file into head of html file.

CSS: 
- add text-transform: capitalize; on .randomPizzaContainer and remove Capitalize from js file.
- add will-change: transform on elements that will change 

JS:
- create an array with adjectives and nouns in order to remove switch / case statements.
- removed useless var declarations from generators functions.
- create a new pizzaGenerator based on jQuery
- optimize resize slider based on jQuery, and add sizeLabel into collection in order to remove switch / case statements.
- optimize updatePositions

IMAGES: 
- resize and optimize.