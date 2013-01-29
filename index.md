---
layout: default
title: Book
---

# Welcome to the Book of Bitovi!

Here you'll learn, or be pointed to, practically everything you need to 
know to build a modern JavaScript application. This is not an
API reference. You can find those elsewhere.  Instead, this is designed
to give you a general understanding so that any gaps can be immediately filled.

By __JavaScript application__ we mean an app where JavaScript is building most of the 
app's HTML and is communicating with the server via AJAX services.

## JavaScript `Justin + Fara`

Mastering JavaScript is the first step in building a JavaScript application. Unfortunately, many think 
that libraries like 
jQuery, Backbone, or even CanJS are short-cuts around fully understanding JavaScript.  They aren't.

Fortunately, JavaScript is one of most simple languages understand because it's designed to be easy to 
implement.
You just have to throw 
out everything you know about most other languages.

So, the first step in understanding JavaScript is to understand it's place in the universe ... that is
it's place in the Browser.

### JS + DOM = Browser

JavaScript is not the [Document Object Model](http://en.wikipedia.org/wiki/Document_Object_Model) (DOM). The DOM is an 
API for interacting with n HTML document.  The DOM is what lets you get an element on the page by id via JavaScript with:

```
var age = document.getElementById('age')
```

The DOM is not part of JavaScript.  JavaScript is a brand-name for the standardized 
language known as [ECMAScript](http://en.wikipedia.org/wiki/ECMAScript).  


The following video helps describe how the DOM and JavaScript work together by detailing what happens when
 the browser loads a page like:

{% highlight html %}
<html>
  <head>
    <script type='text/javascript'>
      alert('hello js');
    </script>
  </head>
  <body>
    <h1>Hello DOM</h1>
  </body>
</html>
{% endhighlight %}


<iframe width="640" height="480" src="http://www.youtube.com/embed/4P8tNC3TZDM" frameborder="0" allowfullscreen="true">
What happens when a browser opens a webpage
</iframe>

### Dynamic

JavaScript is 
a [dynamic](http://en.wikipedia.org/wiki/Dynamic_programming_language) language. Each
statement is run one at a time and builds up the application's structure in memory.

For example, lets see how JavaScript runs the following code:

{% highlight javascript %}
var str = "Project";
{% endhighlight %}

First, the right-hand-side of the "=" operator is evaluated. This
results in "Project" being created in memory like:

Address | Value | Description
------------ | -------------
x1000 | ... | 
x1001 | string | the type
x1002 | project | the string's data
x1003 | ...

Next, the left hand side `var str` is run. This creates
a variable in the current _call object_ (we'll learn more about this in a second) like:

Address | Value
------------ | -------------
... | ...
x1001 | string
x1002 | project
... | ...
x2001 | call object
x2002 | 2
x2003 | str
x2004 | _empty_


### Closures

### Prototypes

## jQuery and the DOM `Justin + Fara`

## Thin Server Architecture `Curtis`

## Dependency Management `Mihael`

## Building Small Components `Austin`

## Assembling Small Components

## Performance

### Building an app

## Testing `Alexis`

## Documentation
