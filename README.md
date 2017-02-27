# Flexbox and Media Queries Lecture
<hr>

### What is flexbox?
Flexbox is a CSS display property that aims to create a better way to layout and align items within a parent container. Flexbox is best suited to creating small components of a website.

### Why use flexbox?
Flexbox allows us to put elements inside of a container, and have that container decide how to shrink/expand/wrap those elements to fill the space available. It also allows us to specify how the items are arranged and ordered.

### How to use

We will be walking through using the included HTML and CSS file. Flexbox has two axis that we can use to organize our elements, the main-axis and the cross-axis. By default the main-axis is horizontal and the cross-axis is vertical.  

![flexbox axis](https://cdn-images-1.medium.com/max/800/1*_Ruy6jFG7gUpSf76IUcJTQ.png)

By default a flex container will put all elements on the main axis with no wrapping, even it it has to shrink the elements. Lets try it!

In the index.css file give container class the `display: flex;` property. Reload the HTML page. What has happened?
