## Website Performance Optimization portfolio project

### About
The main objective of this project was to increase the page speed of Cameron Pittman's portfolio. To do so, I have optmized the Critical Rendering Path of the website and other techniques suggested in the Website Optimization Webcasts.


### Goals
- Have a score of 90 or higher in both mobile and desktop for Cam's index.html, using the Pagespeed website.
- Get 60 FPS score  while scrolling in pizza.html page

### How to Run
To run this project simply go to my Github repository https://github.com/Tsampaio/Website-Optimization and download all the files,
Click on index.html to get started!

#### Part 1: Optimize PageSpeed Insights score for index.html

##### Changes made:

- added media="print" to the print.css
- moved the scripts and style.css to the bottom page so the html can render faster
- inline style.css and print.css

#### Part 2: Optimize Frames per Second in Pizza.html

##### Changes made:

- in the var items replaced the .querySelectorAll by .getElementsByClassName to select the class ".mover"
- removed the phase from the "for loop" to not be calculated all the time
- added the css3 hardware acceleration "transform" to items[i].style like it was suggested in the Webcast "Increase Frame Rate FPS"
- render the pizzas into individual layers using the " css hack" backface-visibility: hiden on the class ".mover"
- reduced the number of element pizzas from 200 to 30, because we can only see a handful of them in the screen

### Project URL

This project is currently hosted at:

http://79.170.40.241/weboptimization.com/


