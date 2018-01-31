## Website Performance Optimization portfolio project

The aim of this project was to remove all the jank slowing the site down and make it optimized so that you don't feel the lag.
### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html
1. Download/ clone the repo [Udacity Original Project Repo](https://github.com/udacity/frontend-nanodegree-mobile-portfolio)
2. I changed the original url linked to the repo to my link for my repo so I can upload the files to see the site on gitpages. [My gitpages link](https://cybernotes.github.io/udacityWebOpt/)
3. I ran the link into pagespeed to see how it performs and followed the suggestions in an attempt bring the score up.

#### Part 2: Optimize Frames per Second in pizza.html
To optimize pizza.html you will need to make adjustments in main.js to make it run at a more stable 60fps. This will prevent any jank from appearing.

* Fixed how the slider responded to movement.
* Used getElementById or getElementByClassName instead of querySelectors to make the page more efficient
* Changed the amount of Pizzas from the 200 max it had to 35 to allow for a more stable scrolling experience.

resources used as reference:
https://github.com/NicoleIrene/UWebsiteOptimize
https://github.com/sadaf30/websiteOptimize
