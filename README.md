# A-Path-To-Web-Developer

## Table of Contents
* **Learning Path**
    * [Front-end Developer roadmap](#roadmap-for-front-end-developer)
    * [IBM job requirements](#ibm-front-end-developer-interns)   


 >Based on roadmap and job requirements   
 >Creating learning objects...

* [HTML(Hypertext Markup Language)](#htmlhypertext-markup-language)
* [CSS(Cascading Style Sheets)](#csscascading-style-sheets)
* [Javascript](#javascript)
* [DOM](#dom)
* [Bootstrap](#bootstrap)
* [JQuery](#jquery)
* [Node.js](#nodejs)
* [Angular.js](#angularjs-1)
* [Ruby](#ruby)
* [Backbone.js](#backbonejs)
* [React](#react)
* [Ember.js](#emberjs)
* [The fundamentals of user interface design](#the-fundamentals-of-user-interface-design)

### Courses to take
* Web Development Foundations: Full-Stack vs Front-End
* Web Programming Foundations
* Programming Foundations: Fundamentals
* User Experience for Web Design
* UX Foundations: Accessibility
* HTML Essential Training
* CSS Essential Training 1
* CSS Essential Training 2
* CSS Essential Training 3
* JavaScript Essential Training
* Responsive Layout
* Learning GitHub
* Bootstrap 4 Essential Training
* Sass Essential Training
* Learning React.js

### References
Frontendmasters book: https://frontendmasters.com/books/front-end-handbook/2019/#1
freecodecamp: https://learn.freecodecamp.org/
____________________________________________________________________________________
### Roadmap for front-end Developer
![Road map for front-end Developer](https://github.com/qiinori/A-Path-To-Web-Developer/blob/master/images/frontend-transparent.png)
from https://roadmap.sh/frontend

### Sample intern job requirement 
IBM Front-End Developer Interns
![IBM Logo](https://github.com/qiinori/A-Path-To-Web-Developer/blob/master/images/IBM%20logo.PNG "IBM")
>Front-End Developer Interns:
Have passion and experience for building responsive, elegant and engaging experiences with future friendly web technologies.
Work closely with designers to take wireframes from conception to implementation and design and improve user interfaces
Work with the IBM Design System to implement UIs
Work in JavaScript, Node.js or frameworks such as React, Vue or Angular
Are skilled in UI Development technologies such as HTML, CSS, JSON and API usage
Have an interest in, understanding of, or experience with Design Thinking Methodology
Have an interest in, understanding of, or experience with Agile development methodology
>
>What You’ll Do:
You’ll work in an Agile, collaborative environment to understand requirements, design, code and test innovative applications, and support those applications for our highly valued customers.
You’ll employ IBM’s Design Thinking to create products that provide a great user experience along with high performance, security, quality, and stability.
At the nexus of engineering and design, you will be instrumental in bringing industry-defining software products, cloud services and web applications to users around the world
>
>Who You Are:
You are highly motivated and have a passion for creating and supporting great products.
You thrive on collaboration, working side by side with people of all backgrounds and disciplines, and you have very strong verbal and written communication skills.
You are great at solving problems, debugging, troubleshooting, designing and implementing solutions to complex technical issues.
You have a basic understanding of software development and programming languages.
>
>Must have basic knowledge in one or more of the following technology areas: Java, Ruby, Python, Javascript, HTML, CSS, Node.js, Angular.js
Knowledge of Backbone.js, Angular.js, React, Ember.js, Bootstrap, Node.js, and JQuery
Willing to travel up to 10%    
from   
https://careers.ibm.com/ShowJob/Id/757416/Front-End-Developer-Intern-12-months-(Ottawa,-ON)/?lang=en#?lang=en

### HTML(Hypertext Markup Language)
doc: https://www.w3schools.com/html/default.asp
### CSS(Cascading Style Sheets)
doc: https://www.w3schools.com/css/default.asp
### Javascript
doc: https://www.w3schools.com/js/default.asp
#### Responsive Images Solution
**Picturefill**
**A responsive image polyfill.**

Project site: https://scottjehl.github.io/picturefill/
Github:https://github.com/scottjehl/picturefill

To start using Picturefill download one of the files listed above and reference it from the head section of your HTML document with the following code:
```html
<script src="js/picturefill.js"></script>
```
To allow your page to load more efficiently, we'd recommend adding an async attribute to that script tag as well. This tells the browser that it can load picturefill asynchronously, without waiting for it to finish before loading the rest of the document. If you add this attribute, you'll need to add a line of script before the script tag as well to allow older browsers to recognize picture elements if it encounters them in the page before picturefill has finished loading.

**RECOMMENDED USAGE:**
```html
<!--  Picturefill  -->
  <script>
    // Picture element HTML5 shiv
    document.createElement( "picture" );
  </script>
  <script src="picturefill.js" async></script>
```
Note that if you are already including a recent version of the HTML5 Shiv (sometimes packaged with Modernizr), you may not need this line as it is included there as well. Also, more advanced users may not need this may choose to load Picturefill dynamically using a script loader like Require.js, (AMD and CommonJS support is included in the script).
Note::add on 07.05.2020
### DOM
### Bootstrap
Web Link: https://getbootstrap.com/
**CSS**

```css
<!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
```
**JS**
Many of our components require the use of JavaScript to function. Specifically, they require jQuery, Popper.js, and our own JavaScript plugins. Place the following <script>s near the end of your pages, right before the closing </body> tag, to enable them. jQuery must come first, then Popper.js, and then our JavaScript plugins.

We use jQuery’s slim build, but the full version is also supported.
```html
<!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
```
### Node.js
Web Link: https://nodejs.org/en/
### JQuery
Web Link: https://jquery.com/
### Node.js
Web Link: https://nodejs.org/en/docs/
### Angular.js
Web Link: https://reactjs.org/
### React
### Angular.js
### Ruby
### Backbone.js
### Ember.js
### The fundamentals of user interface design