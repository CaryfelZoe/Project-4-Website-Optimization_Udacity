# Project 4 Website Optimization

1. Open index.html in your browser
2. Review Cam's Portfolio with all his projects
3. Click on Cam's Pizzeria to know about his project of pizza picking.

## How I completed this project?

1. Reviewed the course on Website Performance Optimization using Google PageSpeed.
2. Downloaded the required project assets.
3. Used Chrome Developer Tools to review the current state of various pages within the application and identify areas for improvement.
4. Reviewed the code powering the website and identified areas where I believe modifications are warranted.
5. Made changes and tested those changes using the tools available to determine if they are a performance gain or loss.

### Changes I made for the Website Performance Optimization
    
index.html
1. I Inline the CSS into the HTML
2. I move down all the script tag

main.js
1. In the line 455 I change the .querySelectorAll for a better method: .getElementsByClass
2. In the line 459 I console.log() dx and newwidth to see how crucial these numbers are that need to be calculated inside the For Loop 
3. In the line 508 I change .querySelectorAll to a more efficient way to access DOM 
4. In the line 533 I change the number of pizzas that acctualy appear on the screen
