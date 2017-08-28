## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Instalation
1. Download the GitHub zip file or clone the repository onto your local workstation: 
	* [zip file](https://github.com/a-yasinsky/frontend-nanodegree-mobile-portfolio/archive/master.zip)
	* [git clone](https://github.com/a-yasinsky/frontend-nanodegree-mobile-portfolio)
2. Open a browser window and navigate to the index.html file or views/pizza.html

### Example
You can try the game [here](https://a-yasinsky.github.io/frontend-nanodegree-mobile-portfolio/)


###  Optimizations

#### Part 1: Optimize PageSpeed Insights score for index.html
1. Change image resolution
2. Add media="print" to css
3. Made css inline
4. Moved scripts to the botton, and made them async
5. Minified js, css

#### Part 2: Optimize Frames per Second in pizza.html
1. Inlined css
2. Added will-change to .mover class
3. Made css inline
4. Deleted unused classes in css
5. Minfied css
6. Resized image
7. Made scripta load async
8. Remove moving pizza div from head (html)
9. Deleted dx calculation with using offsetWidth
10. Simplyfied newwidth calculation
11. Rreduced number of pizzas
12. In updatePositions scrollTop moved out the loop
13. querySelectorAll moved out form updatePositions function

