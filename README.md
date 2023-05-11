
# FLEXBOX

## Review: Flexbox

You have learned the most important properties of flexbox. Flexbox is an art and a science; you can use it to make laying out multiple elements a piece of cake. You know everything necessary to begin using it in your own projects.

1. display: flex changes an element to a block-level container with flex items inside of it.
2. display: inline-flex allows multiple flex containers to appear inline with each other.
3. justify-content is used to space items along the main axis.
4. align-items is used to space items along the cross axis.
5. flex-grow is used to specify how much space (and in what proportions) flex items absorb along the main axis.
6. flex-shrink is used to specify how much flex items shrink and in what proportions along the main axis.
7. flex-basis is used to specify the initial size of an element styled with flex-grow and/or flex-shrink.
8. flex is used to specify flex-grow, flex-shrink, and flex-basis in one declaration.
9. flex-wrap specifies that elements should shift along the cross axis if the flex container is not large enough.
10. align-content is used to space rows along the cross axis.
11. flex-direction is used to specify the main and cross axes.
12. flex-flow is used to specify flex-wrap and flex-direction in one declaration.
13. Flex containers can be nested inside of each other by declaring display: flex or display: inline-flex for children of flex containers.
Let’s apply a few of the properties you’ve learned to arrange one section of the web page in the browser!

All of the images are inside of three column divs and the three column divs are all inside of one large div called .cards.

Inside the .cards ruleset, add a display property with a value of flex.

### Hint
Inside the curly braces of the .cards selector ruleset, the display property should have a value of flex.

```

selector {
  property: value;
}

````
Now, inside the .cards ruleset, set the flex-wrap property to have a value of wrap.

### Hint
flex-wrap should have a value of wrap.

Inside the .cards ruleset, set the justify-content property to have a value of space-around.

### Hint
justify-content should have a value of space-around.

In the .col ruleset, set the display property to have a value of inline-flex.

### Hint
The declaration should be display: inline-flex;

In the .col ruleset, set the flex-direction property to have a value of column.

### Hint
Inside the curly braces of the .col selector ruleset, the flex-direction property should have a value of column.

```
selector {
  property: value;
}

```
In the .col ruleset, set the justify-content property to have a value of space-between.

### Hint
Inside the curly braces of the .col selector ruleset, the justify-content property should have a value of space-between.

```
selector {
  property: value;
}
```



