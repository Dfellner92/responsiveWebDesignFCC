### Change the Color of Text

Change your `h2` element's style so that its text color is red.

```html
<h2 style="color: red;">CatPhotoApp</h2>
```

### Use CSS Selectors to Style Elements

Delete your `h2` element's style attribute, and instead create a CSS `style` block. Add the necessary CSS to turn all `h2` elements blue.

```html
<style>
  h2 {
    color: red;
  }
</style>
<h2>CatPhotoApp</h2>
```

### Use a CSS Class to Style an Element

Inside your `style` element, change the `h2` selector to `.red-text` and update the color's value from `blue` to `red`.

Give your `h2` element the `class` attribute with a value of `red-text`.

```html
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
```

### Style Multiple Elements with a CSS Class

Apply your `red-text` class to the first `p` element.

```html
<p class="red-text">Click here to view more <a href="#">cat photos</a>.</p>
```

### Change the Font Size of an Element

Inside the same `<style>` tag that contains your `red-text` class, create an entry for `p` elements and set the `font-size` to 16 pixels (`16px`).

```html
<style>
  .red-text {
    color: red;
  }
  p {
    font-size: 16px;
  }
</style>
```

### Set the Font Family of an Element

Make all of your `p` elements use the `monospace` font.

```html
<style>
  .red-text {
    color: red;
  }

  p {
    font-size: 16px;
    font-family: monospace;
  }
</style>
```

### Import a Google Font

Import the `Lobster` font to your web page. Then, use an element selector to set `Lobster` as the `font-family` for your `h2` element.

```html
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">

<style>
  .red-text {
    color: red;
  }
  h2 {
    font-family: Lobster;
  }
```

### Specify How Fonts Should Degrade

To begin, apply the `monospace` font to the `h2` element, so that it now has two fonts - `Lobster` and `monospace`.

In the last challenge, you imported the `Lobster` font using the `link` tag. Now comment out that import of the `Lobster` font (using the HTML comments you learned before) from Google Fonts so that it isn't available anymore. Notice how your `h2` element degrades to the `monospace` font.

```html
<!--<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">-->
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, monospace;
  }
```

### Size Your Images

Create a class called `smaller-image` and use it to resize the image so that it's only 100 pixels wide.

```css
.smaller-image {
  width: 100px;
}
```

### Add Borders Around Your Elements

Create a class called `thick-green-border`. This class should add a 10px, solid, green border around an HTML element. Apply the class to your cat photo.

```css
.thick-green-border {
  border-color: green;
  border-width: 10px;
  border-style: solid;
}
```

### Add Rounded Corners with border-radius

You can specify a `border-radius` with pixels. Give your cat photo a `border-radius` of `10px`.

```css
.thick-green-border {
  border-color: green;
  border-width: 10px;
  border-style: solid;
  border-radius: 10px;
}
```

### Make Circular Images with a border-radius

Give your cat photo a `border-radius` of `50%`.

```css
.thick-green-border {
  border-color: green;
  border-width: 10px;
  border-style: solid;
  border-radius: 50%;
}
```

### Give a Background Color to a div Element

Create a class called `silver-background` with the `background-color` of `silver`. Assign this class to your `div` element.

```html
<div class="silver-background">
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
</div>
```

### Set the id of an Element

Give your `form` element the id `cat-photo-form`.

```html
<form
  id="cat-photo-form"
  action="https://freecatphotoapp.com/submit-cat-photo"
></form>
```

### Use an id Attribute to Style an Element

Try giving your form, which now has the `id` attribute of `cat-photo-form`, a green background.

```css
#cat-photo-form {
  background-color: green;
}
```

### Adjust the Padding of an Element

Change the `padding` of your blue box to match that of your red box.

```css
.red-box {
  background-color: crimson;
  color: #fff;
  padding: 20px;
}

.blue-box {
  background-color: blue;
  color: #fff;
  padding: 20px;
}
```

### Adjust the Margin of an Element

Change the `margin` of the blue box to match that of the red box.

```css
.red-box {
  background-color: crimson;
  color: #fff;
  padding: 20px;
  margin: 20px;
}

.blue-box {
  background-color: blue;
  color: #fff;
  padding: 20px;
  margin: 20px;
}
```

### Add a Negative Margin to an Element

Try to set the `margin` to a negative value like the one for the red box.

Change the `margin` of the blue box to `-15px`, so it fills the entire horizontal width of the yellow box around it.

```css
.red-box {
  background-color: crimson;
  color: #fff;
  padding: 20px;
  margin: -15px;
}

.blue-box {
  background-color: blue;
  color: #fff;
  padding: 20px;
  margin: -15px;
}
```

### Add Different Padding to Each Side of an Element

Give the blue box a `padding` of `40px` on its top and left side, but only `20px` on its bottom and right side.

```css
.blue-box {
  background-color: blue;
  padding-top: 40px;
  padding-left: 40px;
  padding-bottom: 20px;
  padding-right: 20px;
  color: #fff;
}
```

### Add Different Margins to Each Side of an Element

Give the blue box a `margin` of `40px` on its top and left side, but only `20px` on its bottom and right side.

```css
.blue-box {
  background-color: blue;
  margin-top: 40px;
  margin-left: 40px;
  margin-bottom: 20px;
  margin-right: 20px;
  color: #fff;
}
```

### Use Clockwise Notation to Specify the Padding of an Element

Use Clockwise Notation to give the `.blue-box` class a `padding` of `40px` on its top and left side, but only `20px` on its bottom and right side.

```css
.blue-box {
  background-color: blue;
  padding: 40px 20px 20px 40px;
  color: #fff;
}
```

### Use Clockwise Notation to Specify the Margin of an Element

Use Clockwise Notation to give the element with the `blue-box` class a margin of `40px` on its top and left side, but only `20px` on its bottom and right side.

```css
.blue-box {
  background-color: blue;
  margin: 40px 20px 20px 40px;
  color: #fff;
}
```

### Use Attribute Selectors to Style Elements

Using the `type` attribute selector, try to give the checkboxes in CatPhotoApp a top margin of 10px and a bottom margin of 15px.

```css
[type="checkbox"] {
  margin: 10px 0 15px;
}
```

### Understand Absolute versus Relative Units

Add a `padding` property to the element with class `red-box` and set it to `1.5em`.

```css
.red-box {
  background-color: red;
  padding: 1.5em;
  margin: 20px 40px 20px 40px;
}
```

### Style the HTML Body Element

Give the body a `background-color` of `black`.

```html
<style>
  body {
    background-color: black;
  }
</style>
```

### Inherit Styles from the Body Element

First, create a `h1` element with the text `Hello World`

Then, let's give all elements on your page the color of `green` by adding `color: green;` to your `body` element's style declaration.

Finally, give your `body` element the `font-family` of monospace by adding `font-family: monospace;` to your `body` element's style declaration.

```html
<style>
  body {
    background-color: black;
    color: green;
    font-family: monospace;
  }
</style>

<h1>Hello World</h1>
```

### Prioritize One Style Over Another

Create a CSS class called `pink-text` that gives an element the color pink.

Give your `h1` element the class of `pink-text`.

```html
<style>
  body {
    background-color: black;
    font-family: monospace;
    color: green;
  }
  .pink-text {
    color: pink;
  }
</style>
<h1 class="pink-text">Hello World!</h1>
```

### Override Styles in Subsequent CSS

Create an additional CSS class called `blue-text` that gives an element the color blue. Make sure it's below your `pink-text` class declaration.

Apply the `blue-text` class to your `h1` element in addition to your `pink-text` class, and let's see which one wins.

```html
<style>
  .pink-text {
    color: pink;
  }
  .blue-text {
    color: blue;
  }
</style>
<h1 class="pink-text blue-text">Hello World!</h1>
```

### Override Class Declarations by Styling ID Attributes

Give your `h1` element the `id` attribute of `orange-text`.

```html
<style>
  #orange-text {
    color: orange;
  }
</style>
<h1 id="orange-text" class="pink-text blue-text">Hello World!</h1>
```

### Override Class Declarations with Inline Styles

Use an inline style to try to make our `h1` element white.

```html
<h1 style="color: white;" id="orange-text" class="pink-text blue-text">
  Hello World!
</h1>
```

### Override All Other Styles by using Important

Let's add the keyword `!important` to your pink-text element's color declaration to make 100% sure that your `h1` element will be pink.

```css
.pink-text {
  color: pink !important;
}
```

### Use Hex Code for Specific Colors

Replace the word `black` in our `body` element's background-color with its hex code representation, `#000000`.

```html
<style>
  body {
    background-color: #000000;
  }
</style>
```

### Use Hex Code to Mix Colors

Replace the color words in our `style` element with their correct hex codes.

```html
<style>
  .red-text {
    color: #ff0000;
  }
  .green-text {
    color: #00ff00;
  }
  .dodger-blue-text {
    color: #1e90ff;
  }
  .orange-text {
    color: #ffa500;
  }
</style>
```

### Use Abbreviated Hex Code

Use the abbreviated hex codes to color the correct elements.

```html
<style>
  .red-text {
    color: #f00;
  }
  .fuchsia-text {
    color: #f0f;
  }
  .cyan-text {
    color: #0ff;
  }
  .green-text {
    color: #0f0;
  }
</style>
```

### Use RGB values to Color Elements

Let's replace the hex code in our `body` element's background color with the RGB value for black: `rgb(0, 0, 0)`

```html
<style>
  body {
    background-color: rgb(0, 0, 0);
  }
</style>
```

### Use RGB to Mix Colors

Replace the hex codes in our `style` element with their correct RGB values.

```html
<style>
  .red-text {
    color: rgb(255, 0, 0);
  }
  .orchid-text {
    color: rgb(218, 112, 214);
  }
  .sienna-text {
    color: rgb(160, 82, 45);
  }
  .blue-text {
    color: rgb(0, 0, 255);
  }
</style>
```

### Use CSS Variables to change several elements at once

In the `penguin` class, change the `black` value to `gray`, the `gray` value to `white`, and the `yellow` value to `orange`.

```html
<style>
  .penguin {
    --penguin-skin: gray;
    --penguin-belly: white;
    --penguin-beak: orange;
  }
</style>
```

### Create a custom CSS Variable

In the `penguin` class, create a variable name `--penguin-skin` and give it a value of `gray`.

```html
<style>
  .penguin {
    --penguin-skin: gray;
  }
</style>
```

### Use a custom CSS Variable

Apply the `--penguin-skin` variable to the `background` property of the `penguin-top`, `penguin-bottom`, `right-hand` and `left-hand` classes.

```html
<style>
  .penguin {
    --penguin-skin: gray;
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }

  .penguin-top {
    top: 10%;
    left: 25%;

    /* Change code below this line */
    background: var(--penguin-skin);
    /* Change code above this line */

    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }
</style>
```

### Attach a Fallback value to a CSS Variable

It looks like there is a problem with the variables supplied to the `.penguin-top` and `.penguin-bottom` classes. Rather than fix the typo, add a fallback value of `black` to the `background` property of the `.penguin-top` and `.penguin-bottom` classes.

```html
<style>
  .penguin {
    --penguin-skin: gray;
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }

  .penguin-top {
    top: 10%;
    left: 25%;

    /* Change code below this line */
    background: var(--penguin-skin, black);
    /* Change code above this line */

    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }
</style>
```

### Improve Compatibility with Browser Fallbacks

It looks like a variable is being used to set the background color of the `.red-box` class. Let's improve our browser compatibility by adding another `background` declaration right before the existing declaration and set its value to `red`.

```html
<style>
  :root {
    --red-color: red;
  }
  .red-box {
    background: red;
    background: var(--red-color);
    height: 200px;
    width: 200px;
  }
</style>
<div class="red-box"></div>
```

### Inherit CSS Variables

Define a variable named `--penguin-belly` in the `:root` selector and give it the value of `pink`. You can then see that the variable is inherited and that all the child elements which use it get pink backgrounds.

```html
<style>
  :root {
    /* Only change code below this line */
    --penguin-belly: pink;
    /* Only change code above this line */
  }

  body {
    background: var(--penguin-belly, #c6faf1);
  }
</style>
```

### Change a variable for a specific area

Change the value of `--penguin-belly` to `white` in the `penguin` class.

```html
<style>
  :root {
    --penguin-skin: gray;
    --penguin-belly: pink;
    --penguin-beak: orange;
  }

  body {
    background: var(--penguin-belly, #c6faf1);
  }

  .penguin {
    /* Only change code below this line */
    --penguin-belly: white;
    /* Only change code above this line */
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }
</style>
```

### Use a media query to change a variable

In the `:root` selector of the `media query`, change it so `--penguin-size` is redefined and given a value of `200px`. Also, redefine `--penguin-skin` and give it a value of `black`. Then resize the preview to see this change in action.

```html
<style>
  :root {
    --penguin-size: 300px;
    --penguin-skin: gray;
    --penguin-belly: white;
    --penguin-beak: orange;
  }

  @media (max-width: 350px) {
    :root {
      /* Only change code below this line */
    --penguin-size: 200px;
    --penguin-skin: black;
      /* Only change code above this line */
    }
  }
</style>
```

