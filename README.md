sass-bootstrap-starter-kit
==========================

Here's my starter kit for working on projects with Bootstrap, Sass and Font Awesome (instead of Glyphicons), and the HTML5 Boilerplate (loosely based). Included are some of my favorite mixins and useful sass things. Using Bootstrap doesn't have to mean your stuff looks boilerplate or is slow... just override the variables for your own style, and be mindful about what CSS and JS you're including. Trust me, you don't need all of it!

* [bootstrap-sass v3.3.6](https://github.com/twbs/bootstrap-sass)
* [Bootstrap JS v3.3.6](https://github.com/twbs/bootstrap)
* [jQuery v2.2.0](http://jquery.com/download/)
* [Font Awesome v4.5.0](https://fortawesome.github.io/Font-Awesome/)

Out of the box, you get to use these classes, in addition to the ones provided by Bootstrap and Font Awesome:

```
.font-sm
.font-md
.font-lg
.font-xl

.top-none
.top-xs
.top-sm
.top-md
.top-lg

.left-none
.left-xs
.left-sm
.left-md
.left-lg

.right-none
.right-xs
.right-sm
.right-md
.right-lg

.bottom-none
.bottom-xs
.bottom-sm
.bottom-md
.bottom-lg
```

### Suggestions:

* If you have the Sass [ruby gem](https://rubygems.org/gems/sass/versions/3.4.21) installed, you can compile sass with `sass sass:css --watch --style nested --sourcemap=none`
* Comment out any of the files in the Bootstrap manifest that you won't need!
* Comment out any of the files in the font-awesome manifest that you won't need!
* Instead of using the `bootstrap.min.js` file, just use the js files that you will actually need.
* You can quickly open a python server to see this by typing `python -m SimpleHTTPServer 4000`
