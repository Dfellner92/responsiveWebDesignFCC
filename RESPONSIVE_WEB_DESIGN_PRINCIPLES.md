### Create a Media Query

Add a media query, so that the `p` tag has a `font-size` of `10px` when the device's height is less than or equal to `800px`.

```html
<style>
  p {
    font-size: 20px;
  }

  /* Only change code below this line */
  @media (max-height: 800px) {
    p {
      font-size: 10px;
    }
  }
  /* Only change code above this line */
</style>
```

### Make an Image Responsive

Add the style rules to the `responsive-img` class to make it responsive. It should never be wider than its container (in this case, it's the preview window) and it should keep its original aspect ratio. After you have added your code, resize the preview to see how your images behave.

```html
<style>
  .responsive-img {
    max-width: 100%;
    height: auto;
  }

  img {
    width: 600px;
  }
</style>

<img
  class="responsive-img"
  src="https://s3.amazonaws.com/freecodecamp/FCCStickerPack.jpg"
  alt="freeCodeCamp stickers set"
/>
<img
  src="https://s3.amazonaws.com/freecodecamp/FCCStickerPack.jpg"
  alt="freeCodeCamp stickers set"
/>
```

### Use a Retina Image for Higher Resolution Displays

Set the `width` and `height` of the `img` tag to half of their original values. In this case, both the original `height` and the original `width` are `200px`.

```html
<style>
  img {
    height: 100px;
    width: 100px;
  }
</style>

<img
  src="https://s3.amazonaws.com/freecodecamp/FCCStickers-CamperBot200x200.jpg"
  alt="freeCodeCamp sticker that says 'Because CamperBot Cares'"
/>
```

### Make Typography Responsive

Set the `width` of the `h2` tag to 80% of the viewport's width and the `width` of the paragraph as 75% of the viewport's smaller dimension.

```html
<style>
  h2 {
    width: 80vw;
  }
  p {
    width: 75vmin;
  }
</style>

<h2>Importantus Ipsum</h2>
<p>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis tempus
  massa. Aenean erat nisl, gravida vel vestibulum cursus, interdum sit amet
  lectus. Sed sit amet quam nibh. Suspendisse quis tincidunt nulla. In hac
  habitasse platea dictumst. Ut sit amet pretium nisl. Vivamus vel mi sem.
  Aenean sit amet consectetur sem. Suspendisse pretium, purus et gravida
  consequat, nunc ligula ultricies diam, at aliquet velit libero a dui.
</p>
```
