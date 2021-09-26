### Say Hello to HTML Elements

To pass the test on this challenge, change your `h1` element's text to say `Hello World`.

```html
<h1>Hello World</h1>
```

### Headline with the h2 Element

Add an `h2` tag that says "CatPhotoApp" to create a second HTML element below your "Hello World" `h1` element.

```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
```

### Inform with the Paragraph Element

Create a p element below your h2 element, and give it the text Hello Paragraph.

```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>Hello Paragraph</p>
```

### Fill in the Blank with Placeholder Text

Replace the text inside your `p` element with the first few words of this kitty ipsum text: `Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.`

```html
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
```

### Uncomment HTML

Uncomment your `h1`, `h2` and `p` elements.

```html
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
```

### Comment out HTML

Comment out your `h1` element and your `p` element, but not your `h2` element.

```html
<!--
<h1>Hello World</h1>
-->
<h2>CatPhotoApp</h2>
<!--
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
-->
```

### Delete HTML Elements

Delete your `h1` element so we can simplify our view.

```html
<h2>CatPhotoApp</h2>

<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
```

### Introduction to HTML5 Elements

Then, create a `main` element and nest only the two `p` elements inside the `main` element.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>

  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

### Add Images to Your Website

Within the existing `main` element, insert an `img` element before the existing `p` elements.

Now set the `src` attribute so that it points to the url `https://www.bit.ly/fcc-relaxing-cat`

Finally, don't forget to give your `img` element an `alt` attribute with applicable text.

```html
<h2>CatPhotoApp</h2>
<main>
  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute cat" />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

### Link to External Pages with Anchor Elements

Create an `a` element that links to `https://www.freecatphotoapp.com` and has "cat photos" as its anchor text.

```html
<h2>CatPhotoApp</h2>
<main>
  <a href="https://www.freecatphotoapp.com">cat photos</a>

  <img
    src="https://www.bit.ly/fcc-relaxing-cat"
    alt="A cute orange cat lying on its back."
  />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

### Link to Internal Sections of a Page with Anchor Elements

Change your external link to an internal link by changing the `href` attribute to `"#footer"` and the text from `cat photos` to `Jump to Bottom`.

Remove the `target="_blank"` attribute from the anchor tag since this causes the linked document to open in a new window tab.

Then add an `id` attribute with a value of `footer` to the `<footer>` element at the bottom of the page.

```html
<h2>CatPhotoApp</h2>
<main>
  <a href="#footer">Jump to Bottom</a>

  <img
    src="https://www.bit.ly/fcc-relaxing-cat"
    alt="A cute orange cat lying on its back."
  />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed
    everywhere rip the couch sleep in the sink fluffy fur catnip scratched.
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
</main>

<footer id="footer">Copyright Cat Photo App</footer>
```

### Nest an Anchor Element within a Paragraph

Nest the existing `a` element within a new `p` element. Do not create a new anchor tag. The new paragraph should have text that says `View more cat photos`, where `cat photos` is a link, and the rest is plain text.

```html
<h2>CatPhotoApp</h2>
<main>
  <img
    src="https://www.bit.ly/fcc-relaxing-cat"
    alt="A cute orange cat lying on its back."
  />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
  <p>
    View more
    <a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a>
  </p>
</main>
```

### Make Dead Links Using the Hash Symbol

The current value of the `href` attribute is a link that points to "`https://www.freecatphotoapp.com`". Replace the `href` attribute value with a `#`, also known as a hash symbol, to create a dead link.

For example: `href="#"`

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#" target="_blank">cat photos</a>.</p>

  <img
    src="https://www.bit.ly/fcc-relaxing-cat"
    alt="A cute orange cat lying on its back."
  />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

### Turn an Image into a Link

Place the existing image element within an `a` (anchor) element.

Once you've done this, hover over your image with your cursor. Your cursor's normal pointer should become the link clicking pointer. The photo is now a link.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="http://www.youtube.com"
    ><img
      src="https://www.bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

### Turn an Image into a Link

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://www.bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

### Create a Bulleted Unordered List

Remove the last two `p` elements and create an unordered list of three things that cats love at the bottom of the page.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://www.bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <ul>
    <li>Food</li>
    <li>Toys</li>
    <li>Milk</li>
  </ul>
</main>
```

### Create an Ordered List

Create an ordered list of the top 3 things cats hate the most.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://www.bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>

  <ol>
    <li>Tail Pulling</li>
    <li>Water</li>
    <li>Dogs</li>
  </ol>
</main>
```

### Create a Text Field

Create an `input` element of type `text` below your lists.

```html
<input type="text" />
```

### Add Placeholder Text to a Text Field

Set the `placeholder` value of your text `input` to "cat photo URL".

```html
<input type="text" placeholder="cat photo URL" />
```

### Create a Form Element

Nest the existing `input` element inside a `form` element and assign `"https://www.freecatphotoapp.com/submit-cat-photo"` to the `action` attribute of the `form` element.

```html
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
  <input type="text" placeholder="cat photo URL" />
</form>
```

### Add a Submit Button to a Form

Add a button as the last element of your `form` element with a type of `submit`, and `Submit` as its text.

```html
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
  <input type="text" placeholder="cat photo URL" />
  <button type="submit">Submit</button>
</form>
```

### Use HTML5 to Require a Field

Make your text `input` a `required` field, so that your user can't submit the form without completing this field.

Then try to submit the form without inputting any text. See how your HTML5 form notifies you that the field is required?

```html
<input type="text" required placeholder="cat photo URL" />
```

### Create a Set of Radio Buttons

Add a pair of radio buttons to your form, each nested in its own `label` element. One should have the option of `indoor` and the other should have the option of `outdoor`. Both should share the name attribute of `indoor-outdoor` to create a radio group.

```html
<label for="indoor">
  Indoor
  <input id="indoor" type="radio" name="indoor-outdoor" />
</label>
<label for="outdoor">
  Outdoor
  <input id="outdoor" type="radio" name="indoor-outdoor" />
</label>
```

### Create a Set of Checkboxes

Add to your form a set of three checkboxes. Each checkbox should be nested within its own `label` element. All three should share the `name` attribute of `personality`.

```html
<label for="loving"
  ><input id="loving" type="checkbox" name="personality" /> Loving
</label>
<label for="kind"
  ><input id="kind" type="checkbox" name="personality" /> Kind</label
>
<label for="angry"
  ><input id="angry" type="checkbox" name="personality" /> Angry</label
>
```

### Use the value attribute with Radio Buttons and Checkboxes

Give each of the existing `radio` and `checkbox` inputs the `value` attribute. Do not create any new radio or checkbox elements. Use the input label text, in lowercase, as the value for the attribute.

```html
<label for="indoor"
  ><input id="indoor" value="indoor" type="radio" name="indoor-outdoor" />
  Indoor</label
>
<label for="outdoor"
  ><input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor" />
  Outdoor</label
><br />
<label for="loving"
  ><input id="loving" value="loving" type="checkbox" name="personality" />
  Loving</label
>
<label for="lazy"
  ><input id="lazy" value="lazy" type="checkbox" name="personality" />
  Lazy</label
>
<label for="energetic"
  ><input id="energetic" value="energetic" type="checkbox" name="personality" />
  Energetic</label
>
```

### Check Radio Buttons and Checkboxes by Default

Set the first of your radio buttons and the first of your checkboxes to both be checked by default.

```html
<label for="indoor"
  ><input
    id="indoor"
    type="radio"
    name="indoor-outdoor"
    value="indoor"
    checked
  />
  Indoor</label
>
<label for="outdoor"
  ><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor" />
  Outdoor</label
><br />
<label for="loving"
  ><input
    id="loving"
    type="checkbox"
    name="personality"
    value="loving"
    checked
  />
  Loving</label
>
<label for="lazy"
  ><input id="lazy" type="checkbox" name="personality" value="lazy" />
  Lazy</label
>
<label for="energetic"
  ><input id="energetic" type="checkbox" name="personality" value="energetic" />
  Energetic</label
><br />
```

### Nest Many Elements within a Single div Element

Nest your "Things cats love" and "Top 3 things cats hate" lists all within a single `div` element.

Hint: Try putting your opening `div` tag above your "Things cats love" `p` element and your closing `div` tag after your closing `ol` tag so that both of your lists are within one `div`.

```html
<div>
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
