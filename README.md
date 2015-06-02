## Website Performance Optimization project

### My challenges are:
####1.To optimize an online portfolio for speed. <br>
In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).<br>

I optimized my site and judge it through PageSpeed Insights,commenting every change using"<!-- -->".Finally my site got a speed over 90 score.<br>

1)css and js files has been minified.<br>
2)some css files has been inlined <br>
3)Images have been resized and comressed<br>

check the site here:http://zvdifo.github.io/P4-web-optimization/

####2.Effective Optimizations For 60 FPS<br>
In particular, I need to use the timeline to measure the time it takes to Render and Paint the elements.I mainly modified views/js/main.js.And got something like this.
![alt tag](https://github.com/zvdifo/P4-web-optimization/blob/gh-pages/img/timeline.PNG)

I comment every change using"/* */".<br>
1)Images have been resized and comressed<br>
2)Remove some variables out of the for loops, measure the size of a pizza once.<br>
3)change the amount of moving pizza in background to reduce rendering time.<br>

check the site here:http://zvdifo.github.io/P4-web-optimization/views/pizza.html
