---
layout: default
title: Book
---

# Welcome to Book!

This is the book

## First heading

{% highlight javascript %}
// Some highlighting
var person = new can.Observe({
  first : "Justin",
  last : "Meyer"
});
var fullName = can.compute(function(){
  return person.attr("first") +" "+ person.attr("last")
})

fullName() //-> "Justin Meyer"

fullName.bind("change", function(ev, newVal, oldVal){
  console.log("fullName changed from", oldVal,"to",newVal)
});

person.attr({
  first: "David",
  last: "Luecke"
})
{% endhighlight %}

### What you need to know about JavaScript

### Sub heading 2

## Second heading