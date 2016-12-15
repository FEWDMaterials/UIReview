## [javascript hover implementation](https://github.com/FEWDMaterials/UIReview/tree/master/p4)

Implement CSS ":hover", but with javascript.

When the user puts mouse over the box, it should change color. When the user moves mouse off the box, remove the color.

### Stretch Goals

1. Look into the data- attribute in HTML for a way to define the property that should be updated by your code. 

```html
<!-- FOR EXAMPLE -->

<div class="box" data-rule="background-color" data-value="red"></div>
<!-- ^^^ changes the background color -->

<div class="box" data-rule="border-color" data-value="green"></div>
<!-- ^^^ changes the border color -->

```

2. How can you do what we did above, but with classes?

```html
<!-- FOR EXAMPLE -->

<div class="box" data-classToAdd="foobar"></div>
<!-- ^^^ adds class 'foobar' when hovered -->


<div class="box" data-classToAdd="test"></div>
<!-- ^^^ adds class 'test' when hovered -->

```