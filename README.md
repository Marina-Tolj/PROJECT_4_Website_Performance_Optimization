# PROJECT_4_Website_Performance_Optimization
Two folders: first with the original portfolio and second with optimized version.
To view the optimized one, choose the second folder "frontend-nanodegree-mobile-portfolio-optimized".

To run the website: download folder “frontend-nanodegree-mobile-portfolio-optimized”, and open index.html in your browser.
Optimization steps taken:
In the index.html:
•	render blocking print.css has and added media="print"
•	style.css has been in lined
•	web font is now in the in lined style
•	perfmatters.js in now async and minified. 
All images have been compressed using https://tinypng.com/.

Views folder:
In the pizza.html:
•	Added <meta name="viewport" content="width=device-width"> and <meta name="viewport" content="initial-scale=1">.
•	In lined style.css
•	Minified bootstrap-grid.css
In the main.js:
•	Changed document.querySelectorAll() to document.getElementsByClassName() for speed optimization
•	Reduced the number of pizzas that load on the screen from 200 to 48
•	Declared pizzasDiv variable outside the loop, so the function only makes one DOM call
•	Declared phase variable (var move;) outside the loop , so it is not created every time the loop is executed
•	Declared elem variable (var elem;)  outside the loop , so it is not created every time the loop is executed
•	(in the js folder I left both minified version of main.js and the version with comments, only minified version is being used for the website)
All images have been compressed using https://tinypng.com/.

There is a README file also explaining steps taken to optimize the original portfolio website.

