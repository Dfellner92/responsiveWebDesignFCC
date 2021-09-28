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
    box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);

  }
```