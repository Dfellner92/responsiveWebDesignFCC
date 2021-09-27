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

To begin, apply the ```monospace``` font to the ```h2``` element, so that it now has two fonts - ```Lobster``` and ```monospace```.

In the last challenge, you imported the ```Lobster``` font using the ```link``` tag. Now comment out that import of the ```Lobster``` font (using the HTML comments you learned before) from Google Fonts so that it isn't available anymore. Notice how your ```h2``` element degrades to the ```monospace``` font.

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

###