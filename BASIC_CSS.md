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

Apply your ```red-text``` class to the first ```p``` element.

```html
 <p class="red-text">Click here to view more <a href="#">cat photos</a>.</p>
```