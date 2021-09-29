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
