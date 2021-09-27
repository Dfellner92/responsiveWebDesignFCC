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
