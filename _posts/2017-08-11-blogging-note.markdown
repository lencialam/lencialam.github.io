---
layout: post
title:  "Blogging with Jekyll and Github Pages"
date:   2017-08-11 23:02:00 +0800
categories: ["development", "webapp"]
---

# Jekyll
Run your blog in localhost with `bundle exec jekyll serve` or simply `jekyll serve`

## Show mathematical formula in markdown
### Methods

1. [Google Chart](#method-1)
2. [Forkosh](#method-2)
3. [MathJax](#method-3)

#### <a id="method-1"></a>Google Chart
  Example:
  ```
<img src="http://chart.googleapis.com/chart?cht=tx&chl=\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" style="border:none;">
  ```
  would output the following formula:
  <img src="http://chart.googleapis.com/chart?cht=tx&chl=\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" style="border:none;">

#### <a id="method-2"></a>Forkosh (Not tested)
  Example:
  ```
<img src="http://www.forkosh.com/mathtex.cgi? \Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}">
  ```
  would output the following formula:
  <img src="http://www.forkosh.com/mathtex.cgi? \Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}">

#### <a id="method-3"></a>MathJax
  Example:

  First include it in head:
  ```
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
  ```
  Then:
  + Formula in a new line
  ```
$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
  ```
  $$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
  + Inline formula
  ```
\\(x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}\\)
  ```
  \\(x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}\\)

### LaTex
+ [Online Latex Editor](http://www.codecogs.com/latex/eqneditor.php)
