# challenge-sass
---
## What is sass(scss)?
<i>Sass is a CSS preprocessor.</i>

---
### Being able to explain what a CSS-Preprocessor is:
Sass adds special features such as variables, nested rules and mixins (sometimes referred to as syntactic sugar) into regular CSS. The aim is to make the coding process simpler and more efficient.

---
### Generate some CSS from your CSS preprocessor (SASS)
<a href = "https://sass-lang.com/documentation/syntax">Useful link</a>

---
### Being able to minify your CSS output
Minify in CSS is used to removes the unnecessary characters in our CSS or HTML or JavaScript source code to reduce the file size and make file to load faster than as before minifying.

---
### <b>Knowledge of the following SASS features:</b>
<ol>
<li><b>Variables</b></li>
A variable declaration looks a lot like a property declaration: it’s written <b>"variable": "expression"</b>. Unlike a property, which can only be declared in a style rule or at-rule, variables can be declared anywhere you want. To use a variable, just include it in a value.
<li><b>Mixins (Functions)</b></li>
Mixins are defined using the @mixin at-rule, which is written @mixin "name" { ... } or @mixin name("arguments...") { ... }. A mixin’s name can be any Sass identifier, and it can contain any statement other than top-level statements. They can be used to encapsulate styles that can be dropped into a single style rule; they can contain style rules of their own that can be nested in other rules or included at the top level of the stylesheet; or they can just serve to modify variables.
Mixins are included into the current context using the @include at-rule, which is written @include "name" or @include "name"("arguments..."), with the name of the mixin being included.
<li><b>Nesting</b></li>
When writing HTML you've probably noticed that it has a clear nested and visual hierarchy. CSS, on the other hand, doesn't.
Sass will let you nest your CSS selectors in a way that follows the same visual hierarchy of your HTML. 
<i>Be aware that overly nested rules will result in over-qualified CSS that could prove hard to maintain and is generally considered bad practice.</i>
<li><b>Partials & Import</b></li>
You can create partial Sass files that contain little snippets of CSS that you can include in other Sass files. This is a great way to modularize your CSS and help keep things easier to maintain. A partial is a Sass file named with a leading underscore. You might name it something like _partial.scss. The underscore lets Sass know that the file is only a partial file and that it should not be generated into a CSS file. Sass partials are used with the @use rule.
<li><b>Extend/Inheritance</b></li>
Using @extend lets you share a set of CSS properties from one selector to another. In our example we're going to create a simple series of messaging for errors, warnings and successes using another feature which goes hand in hand with extend, placeholder classes. A placeholder class is a special type of class that only prints when it is extended, and can help keep your compiled CSS neat and clean.
<li><b>Operators (Math)</b></li>
Doing math in your CSS is very helpful. Sass has a handful of standard math operators like +, -, *, math.div(), and %. In our example we're going to do some simple math to calculate widths for an article and aside.
</ol>

---
## <b>Links</b>
<a href = "https://sass-lang.com/guide">sass basics</a> <br>
<a href = "https://www.w3schools.com/sass/default.php">w3schools</a> <br>
<a href = "https://sass-guidelin.es/">sass guidelines</a>

---
### <b>PS: 
all "..." are <...><br>
SCSS and Sass have different syntax