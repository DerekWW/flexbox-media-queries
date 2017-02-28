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

In the index.css file give container class the `display: flex;` property. Reload the HTML page. What has happened? The block level elements have shifted to sit along the main-axis, and also moved to the start of the cross-axis.

![axis-gif](https://cdn-images-1.medium.com/max/1000/1*L2W-ziqU45a1BNWV79ijDQ.gif)

The items inside of the container are now flex items and will adjust based on how the parent container tells them to. We can now start telling the container how to arrange its children.

### main-axis

To change how the children sit along the main axis we use `justify-content` on the container. This rule has several values that do the following:

- `justify-content: flex-start` is the default value and justify the content to the start of the main-axis
- `justify-content: flex-end` will do the opposite of flex-start and justify the content to the end of the main axis.
- `justify-content: center` will center the content along the main axis
- `justify-content: space-between` will equally space out the content along the main-axis with any space not taken by content being put between the elements
- `justify-content: space-around` will do the same as above, but also put space on the outside of the elements.

### cross-axis

To change how children sit along the cross-axis we use `align-items` on the container.

- `align-items: flex-start` is the default value and will align the elements to the start of the cross-axis
- `align-items: flex-end` same as above, but to the end of the cross-axis
- `align-items: center` will center the content along the cross-axis
- `align-items: stretch` will have the item take up any remaining room in the container along the cross-axis, but only if the elements do not have a defined height

### flex-direction

We can also tell flexbox where to put the main and cross axis using `flex-direction` on the container

- `flex-direction: row` this is the default and will have the 
- `flex-direction:`
- `flex-direction:`
- `flex-direction:`
