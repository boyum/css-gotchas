---
layout: default
---

# CSS Properties

First, an example of different properties:

```css{all|all|1|2|3|4|5-6|7-9}
.✨ {
  background-color: rebeccapurple;
  border-radius: 2ex;
  box-shadow: 1px 6px 25px 6px #66339955;
  color: rgb(255 255 255 / 1);
  font-family: 'IBM Plex Mono', monospace;
  height: 8rem;
  padding: 16px 2ch;
  width: 12em;
}
```

<br />
<br />

<div v-click="1" style="
  background-color: rebeccapurple;
  border-radius: 2ex;
  box-shadow: 1px 6px 25px 6px #66339955;
  color: rgb(255 255 255 / 1);
  font-family: 'IBM Plex Mono', monospace;
  height: 8rem;
  padding: 16px 2ch;
  width: 12em;
">Hiya 🌼</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&display=swap');
</style>

<!--
First is what's called the selector. We can select a whole lot of things, such as class names, element tags and element ids. CSS supports Unicode, which means we can use any character for the class name, even emoji!

To set the purple background color, we use the `background-color` property. There are many different ways to define colors, and one of them is with color names, such as rebeccapurple, hotpink and tomato.

`border-radius` is a property we use to shave off parts of the element's corners. We can set the value in absolute units, or use percentages. A border-radius of anything more than 50% will make the element circular.

The next property is `box-shadow`. We can use it to add a blurred shadow underneath the element. The shadow will be in the shape of the element, even if we have used border-radius to alter it.

`color` sets the text color of the element. We see the third way of defining a color, all within the same red-green-blue color space.

`height` and `width` sets the dimensions of the element, while lastly `padding` sets the inside spacing of the element – the space between the edge and the content inside. `padding` is actually a shorthand property for `padding-top`, `padding-right`, `padding-bottom`, and `padding-left`, but we'll get to that.
-->
