---
layout: post
title: Jekyll and Sass
date:   2015-11-17 11:53:25
categories: jekyll update
---
###What do you think of pre-compiling your CSS?
* Compare to regular CSS

I personally think that pre-compiling is a way more efficient way too write your CSS code.
No need to repeat yourself over and over again. You write your code once then reuse it on different content.

* Which techniques did you use?

For this blog i've used Jekyll (Static Site Generator) and Sass (Preprocessor).

* Pros
  * You will optimize your code, remove duplicated code by using "mixins" (functions).
  * All your CSS files will add up to one CSS file (less http calls).
  * Since you can use variables in your code it will be a lot easier to organize
and make changes in your CSS.
  * It's easy to make calculations in your CSS.
  * You can nest your code.

* Cons
  * More complex tools, setups, etc..
  * Difficulties to debug your code.

###What do you think of static site generators?
I find it very effective. I like the concept that you can change more than one HTML file at once.

* What type of projects are they suitable for?

It's suitable for plain static websites.
Where you only need a simple web server and no databases.
So the conclusion is that you shouldn't use static site generators for larger websites
that requires a lot maintenance. Instead use it for simple static websites, for instance blogs.
