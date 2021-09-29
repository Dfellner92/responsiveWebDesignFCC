### Create Visual Balance Using the text-align Property

Align the `h4` tag's text, which says "Google", to the center. Then justify the paragraph tag which contains information about how Google was founded.

```html
<style>
  h4 {
    text-align: center;
  }
  p {
    text-align: justify;
  }
</style>
```

### Adjust the Width of an Element Using the width Property

Add a `width` property to the entire card and set it to an absolute value of 245px. Use the `fullCard` class to select the element.

```css
.fullCard {
  width: 245px;
  border: 1px solid #ccc;
  border-radius: 5px;
  margin: 10px 5px;
  padding: 4px;
}
```

### Adjust the Height of an Element Using the height Property

Add a `height` property to the `h4` tag and set it to 25px.

```css
h4 {
  text-align: center;
  height: 25px;
}
```

### Use the strong Tag to Make Text Bold

Wrap a `strong` tag around `Stanford University` text inside the `p` tag (do not include the period).

```html
<p>
  Google was founded by Larry Page and Sergey Brin while they were Ph.D.
  students at <strong>Stanford University</strong>.
</p>
```

### Use the u Tag to Underline Text

Wrap the `u` tag only around the text `Ph.D. students`.

```html
<p>
  Google was founded by Larry Page and Sergey Brin while they were
  <u>Ph.D. students</u> at <strong>Stanford University</strong>.
</p>
```

### Use the em Tag to Italicize Text

Wrap an `em` tag around the contents of the paragraph tag to give it emphasis.

```html
<p>
  <em
    >Google was founded by Larry Page and Sergey Brin while they were
    <u>Ph.D. students</u> at <strong>Stanford University</strong>.</em
  >
</p>
```

### Use the s Tag to Strikethrough Text

Wrap the `s` tag around `Google` inside the `h4` tag and then add the word `Alphabet` beside it, which should not have the strikethrough formatting.

```html
<h4><s>Google</s> Alphabet</h4>
```

### Create a Horizontal Line Using the hr Element

Add an `hr` tag underneath the `h4` which contains the card title.

```html
<h4><s>Google</s>Alphabet</h4>
<hr />
```

### Adjust the background-color Property of Text

To make the text stand out more, adjust the `background-color` of the `h4` element to the given `rgba()` value.

Also for the `h4`, remove the `height` property and add `padding` of 10px.

```css
h4 {
  text-align: center;
  padding: 10px;
  background-color: rgba(45, 45, 45, 0.1);
}
```

### Adjust the Size of a Header Versus a Paragraph Tag

To make the heading significantly larger than the paragraph, change the `font-size` of the `h4` tag to 27 pixels.

```css
h4 {
  font-size: 27px;
  text-align: center;
  background-color: rgba(45, 45, 45, 0.1);
  padding: 10px;
}
```

### Add a box-shadow to a Card-like Element

The element now has an id of `thumbnail`. With this selector, use the example CSS values above to place a `box-shadow` on the card.

```css
#thumbnail {
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23);
}
```

### Decrease the Opacity of an Element

Set the `opacity` of the anchor tags to 0.7 using `links` class to select them

```css
.links {
  text-align: left;
  color: black;
  opacity: 0.7;
}
```

### Use the text-transform Property to Make Text Uppercase

Transform the text of the `h4` to be uppercase using the `text-transform` property.

```css
h4 {
  text-align: center;
  background-color: rgba(45, 45, 45, 0.1);
  padding: 10px;
  font-size: 27px;
  text-transform: uppercase;
}
```

### Set the font-size for Multiple Heading Elements

In the `style` tags, set the `font-size` of the:

`h1` tag to 68px.
`h2` tag to 52px.
`h3` tag to 40px.
`h4` tag to 32px.
`h5` tag to 21px.
`h6` tag to 14px.

```html
<style>
  h1 {
    font-size: 68px;
  }
  h2 {
    font-size: 52px;
  }
  h3 {
    font-size: 40px;
  }
  h4 {
    font-size: 32px;
  }
  h5 {
    font-size: 21px;
  }
  h6 {
    font-size: 14px;
  }
</style>
```

### Set the font-weight for Multiple Heading Elements

Set the `font-weight` of the `h1` tag to 800.
Set the `font-weight` of the `h2` tag to 600.
Set the `font-weight` of the `h3` tag to 500.
Set the `font-weight` of the `h4` tag to 400.
Set the `font-weight` of the `h5` tag to 300.
Set the `font-weight` of the `h6` tag to 200.

```html
<style>
  h1 {
    font-size: 68px;
    font-weight: 800;
  }
  h2 {
    font-size: 52px;
    font-weight: 600;
  }
  h3 {
    font-size: 40px;
    font-weight: 500;
  }
  h4 {
    font-size: 32px;
    font-weight: 400;
  }
  h5 {
    font-size: 21px;
    font-weight: 300;
  }
  h6 {
    font-size: 14px;
    font-weight: 200;
  }
</style>
```

### Set the font-size of Paragraph Text

Change the value of the `font-size` property for the paragraph to 16px to make it more visible.

```html
<style>
  p {
    font-size: 16px;
  }
</style>
```

### Set the line-height of Paragraphs

Add a `line-height` property to the `p` tag and set it to 25px.

```html
<style>
  p {
    font-size: 16px;
    line-height: 25px;
  }
</style>
```

### Adjust the Hover State of an Anchor Tag

The code editor has a CSS rule to style all `a` tags black. Add a rule so that when the user hovers over the `a` tag, the `color` is blue.

```html
<style>
  a {
    color: #000;
  }
  a:hover {
    color: blue;
  }
</style>
```

### Change an Element's Relative Position

Change the `position` of the `h2` to `relative`, and use a CSS offset to move it 15 pixels away from the `top` of where it sits in the normal flow. Notice there is no impact on the positions of the surrounding h1 and p elements.

```html
<style>
  h2 {
    position: relative;
    top: 15px;
  }
</style>
```

### Move a Relatively Positioned Element with CSS Offsets

Use CSS offsets to move the `h2` 15 pixels to the right and 10 pixels up.

```html
<style>
  h2 {
    position: relative;
    left: 15px;
    bottom: 10px;
  }
</style>
```

### Lock an Element to its Parent with Absolute Positioning

Lock the `#searchbar` element to the top-right of its `section` parent by declaring its `position` as `absolute`. Give it `top` and `right` offsets of 50 pixels each.

```html
<style>
  #searchbar {
    position: absolute;
    top: 50px;
    right: 50px;
  }
  section {
    position: relative;
  }
</style>
```

### Lock an Element to the Browser Window with Fixed Positioning

The navigation bar in the code is labeled with an id of `navbar`. Change its `position` to `fixed`, and offset it 0 pixels from the `top` and 0 pixels from the `left`. After you have added the code, scroll the preview window to see how the navigation stays in place.

```css
#navbar {
  position: fixed;
  top: 0px;
  left: 0px;

  width: 100%;
  background-color: #767676;
}
```

### Push Elements Left or Right with the float Property

The given markup would work well as a two-column layout, with the `section` and `aside` elements next to each other. Give the `#left` item a `float` of `left` and the `#right` item a `float` of `right`.

```css
#left {
  float: left;
  width: 50%;
}
#right {
  float: right;
  width: 40%;
}
```

### Change the Position of Overlapping Elements with the z-index Property

Add a `z-index` property to the element with the class name of `first` (the red rectangle) and set it to a value of 2 so it covers the other element (blue rectangle).

```css
.first {
  background-color: red;
  position: absolute;
  z-index: 2;
}
.second {
  background-color: blue;
  position: absolute;
  left: 40px;
  top: 50px;
  z-index: 1;
}
```

### Center an Element Horizontally Using the margin Property

Center the `div` on the page by adding a `margin` property with a value of `auto`.

```html
<style>
  div {
    background-color: blue;
    height: 100px;
    width: 100px;
    margin: auto;
  }
</style>
<div></div>
```

### Learn about Complementary Colors

Change the `background-color` property of the `blue` and `yellow` classes to their respective colors. Notice how the colors look different next to each other than they do compared against the white background.

```css
.blue {
  background-color: #0000ff;
}
.yellow {
  background-color: #ffff00;
}
```

### Learn Tertiary Colors

Change the `background-color` property of the `orange`, `cyan`, and `raspberry` classes to their respective colors. Make sure to use the hex codes and not the color names.

```css
.orange {
  background-color: #ff7f00;
}

.cyan {
  background-color: #00ffff;
}

.raspberry {
  background-color: #ff007f;
}
```

### Adjust the Color of Various Elements to Complementary Colors

This page will use a shade of teal (`#09A7A1`) as the dominant color, and its orange (`#FF790E`) complement to visually highlight the sign-up buttons. Change the `background-color` of both the `header` and `footer` from black to the teal color. Then change the `h2` text `color` to teal as well. Finally, change the `background-color` of the `button` to the orange color.

```html
<style>
  body {
    background-color: white;
  }
  header {
    background-color: #09a7a1;
    color: white;
    padding: 0.25em;
  }
  h2 {
    color: #09a7a1;
  }
  button {
    background-color: FF790E;
  }
  footer {
    background-color: #09a7a1;
    color: white;
    padding: 0.5em;
  }
</style>
```

### Adjust the Hue of a Color

Change the `background-color` of each `div` element based on the class names (`green`, `cyan`, or `blue`) using `hsl()`. All three should have full saturation and normal lightness.

```css
.green {
  background-color: hsl(120, 100%, 50%);
}

.cyan {
  background-color: hsl(180, 100%, 50%);
}

.blue {
  background-color: hsl(240, 100%, 50%);
}
```

### Adjust the Tone of a Color

All elements have a default `background-color` of `transparent`. Our `nav` element currently appears to have a `cyan` background, because the element behind it has a `background-color` set to `cyan`. Add a `background-color` to the `nav` element so it uses the same `cyan` hue, but has `80%` saturation and `25%` lightness values to change its tone and shade.

```css
header {
  background-color: hsl(180, 90%, 35%);
  color: #ffffff;
}

nav {
  background-color: hsl(180, 80%, 25%);
}
```

### Create a Gradual CSS Linear Gradient

Use a `linear-gradient()` for the `div` element's `background`, and set it from a direction of 35 degrees to change the color from `#CCFFFF` to `#FFCCCC`.

```html
<style>
  div {
    border-radius: 20px;
    width: 70%;
    height: 400px;
    margin: 50px auto;
    background: linear-gradient(35deg, #ccffff, #ffcccc);
  }
</style>
```

### Use a CSS Linear Gradient to Create a Striped Element

Make stripes by changing the `repeating-linear-gradient()` to use a gradient angle of `45deg`, then set the first two color stops to `yellow`, and finally the second two color stops to `black`.

```html
<style>
  div {
    border-radius: 20px;
    width: 70%;
    height: 400px;
    margin: 50 auto;
    background: repeating-linear-gradient(
      45deg,
      yellow 0px,
      yellow 40px,
      black 40px,
      black 80px
    );
  }
</style>

<div></div>
```

### Create Texture by Adding a Subtle Pattern as a Background Image

Using the url of `https://cdn-media-1.freecodecamp.org/imgr/MJAkxbh.png`, set the `background` of the whole page with the `body` selector.

```html
<style>
  body {
    background: url(https://cdn-media-1.freecodecamp.org/imgr/MJAkxbh.png);
  }
</style>
```

### Use the CSS Transform scale

Increase the size of the element with the id of `ball2` to 1.5 times its original size.

```html
<style>
  .ball {
    width: 40px;
    height: 40px;
    margin: 50 auto;
    position: fixed;
    background: linear-gradient(35deg, #ccffff, #ffcccc);
    border-radius: 50%;
  }
  #ball1 {
    left: 20%;
  }
  #ball2 {
    left: 65%;
    transform: scale(1.5);
  }
</style>

<div class="ball" id="ball1"></div>
<div class="ball" id="ball2"></div>
```

### Use the CSS Transform scale Property to Scale an Element on Hover

Add a CSS rule for the hover state of the `div` and use the `transform` property to scale the `div` element to 1.1 times its original size when a user hovers over it.

```html
<style>
  div {
    width: 70%;
    height: 100px;
    margin: 50px auto;
    background: linear-gradient(53deg, #ccfffc, #ffcccf);
  }
  div:hover {
    transform: scale(1.1);
  }
</style>

<div></div>
```

### Use the CSS Transform Property skewX to Skew an Element Along the X-Axis

Skew the element with the id of `bottom` by 24 degrees along the X-axis by using the `transform` property.

```html
<style>
  div {
    width: 70%;
    height: 100px;
    margin: 50px auto;
  }
  #top {
    background-color: red;
  }
  #bottom {
    background-color: blue;
    transform: skewX(24deg);
  }
</style>

<div id="top"></div>
<div id="bottom"></div>
```

### Use the CSS Transform Property skewY to Skew an Element Along the Y-Axis

Skew the element with the id of `top` -10 degrees along the Y-axis by using the `transform` property.

```html
<style>
  div {
    width: 70%;
    height: 100px;
    margin: 50px auto;
  }
  #top {
    background-color: red;
    transform: skewY(-10deg);
  }
  #bottom {
    background-color: blue;
    transform: skewX(24deg);
  }
</style>

<div id="top"></div>
<div id="bottom"></div>
```

### Create a Graphic Using CSS

Manipulate the square element in the editor to create the moon shape. First, change the `background-color` to `transparent`, then set the `border-radius` property to 50% to make the circular shape. Finally, change the `box-shadow` property to set the `offset-x` to 25px, the `offset-y` to 10px, `blur-radius` to 0, `spread-radius` to 0, and color to `blue`.

```html
<style>
  .center {
    position: absolute;
    margin: auto;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100px;
    height: 100px;
    background-color: transparent;
    border-radius: 50%;
    box-shadow: 25px 10px 0 0 blue;
  }
</style>
<div class="center"></div>
```

### Create a More Complex Shape Using CSS and HTML

Transform the element on the screen to a heart. In the `heart::after` selector, change the `background-color` to `pink` and the `border-radius` to 50%.

Next, target the element with the class `heart` (just `heart`) and fill in the `transform` property. Use the `rotate()` function with -45 degrees.

Finally, in the `heart::before` selector, set its `content` property to an empty string.

```html
<style>
  .heart {
    position: absolute;
    margin: auto;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background-color: pink;
    height: 50px;
    width: 50px;
    transform: rotate(-45deg);
  }
  .heart::after {
    background-color: pink;
    content: "";
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: 0px;
    left: 25px;
  }
  .heart::before {
    content: "";
    background-color: pink;
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: -25px;
    left: 0px;
  }
</style>
<div class="heart"></div>
```

### Learn How the CSS @keyframes and animation Properties Work

Create an animation for the element with the id `rect`, by setting the `animation-name` to `rainbow` and the `animation-duration` to 4 seconds. Next, declare a `@keyframes` rule, and set the `background-color` at the beginning of the animation (`0%`) to blue, the middle of the animation (`50%`) to green, and the end of the animation (`100%`) to yellow.

```html
<style>
  div {
    height: 40px;
    width: 70%;
    background: black;
    margin: 50px auto;
    border-radius: 5px;
  }

  #rect {
    animation-name: rainbow;
  animation-duration: 4s;

  }

  @keyframes rainbow {
    0% {
      background-color: blue;
    }
    50% {
     background-color: green; 
    }
    100% {
      background-color: yellow;
    }
  }




</style>
<div id="rect"></div>
```

###