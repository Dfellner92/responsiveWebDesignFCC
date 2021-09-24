### Say Hello to HTML Elements

To pass the test on this challenge, change your ```h1``` element's text to say ```Hello World```.

```html
<h1>Hello World</h1>
```
### Headline with the h2 Element

Add an ```h2``` tag that says "CatPhotoApp" to create a second HTML element below your "Hello World" ```h1``` element.

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

Replace the text inside your ```p``` element with the first few words of this kitty ipsum text: ```Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.```

```html
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

### Uncomment HTML

Uncomment your ```h1```, ```h2``` and ```p``` elements.

```html
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

### Comment out HTML

Comment out your ```h1``` element and your ```p``` element, but not your ```h2``` element.

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

Delete your ```h1``` element so we can simplify our view.

```html
<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

### Introduction to HTML5 Elements

Then, create a ```main``` element and nest only the two ```p``` elements inside the ```main``` element.

```html
<h2>CatPhotoApp</h2>
<main>
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>

<p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

### Add Images to Your Website

Within the existing ```main``` element, insert an ```img``` element before the existing ```p``` elements.

Now set the ```src``` attribute so that it points to the url ```https://www.bit.ly/fcc-relaxing-cat```

Finally, don't forget to give your ```img``` element an ```alt``` attribute with applicable text.

```html
<h2>CatPhotoApp</h2>
<main>
  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute cat">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

### Link to External Pages with Anchor Elements

Create an ```a``` element that links to ```https://www.freecatphotoapp.com``` and has "cat photos" as its anchor text.

```html
<h2>CatPhotoApp</h2>
<main>

<a href="https://www.freecatphotoapp.com">cat photos</a>

  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

### Link to Internal Sections of a Page with Anchor Elements

Change your external link to an internal link by changing the ```href``` attribute to ```"#footer"``` and the text from ```cat photos``` to ```Jump to Bottom```.

Remove the ```target="_blank"``` attribute from the anchor tag since this causes the linked document to open in a new window tab.

Then add an ```id``` attribute with a value of ```footer``` to the ```<footer>``` element at the bottom of the page.

```html
<h2>CatPhotoApp</h2>
<main>

  <a href="#footer">Jump to Bottom</a>

  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>

</main>

<footer id="footer">Copyright Cat Photo App</footer>
```

### Nest an Anchor Element within a Paragraph

Nest the existing ```a``` element within a new ```p``` element. Do not create a new anchor tag. The new paragraph should have text that says ```View more cat photos```, where ```cat photos``` is a link, and the rest is plain text.

```html
<h2>CatPhotoApp</h2>
<main>

  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <p>View more <a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a></p>
</main>
```

### Make Dead Links Using the Hash Symbol

The current value of the ```href``` attribute is a link that points to "```https://www.freecatphotoapp.com```". Replace the ```href``` attribute value with a ```#```, also known as a hash symbol, to create a dead link.

For example: ```href="#"```

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#" target="_blank">cat photos</a>.</p>

  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

### Turn an Image into a Link

Place the existing image element within an ```a``` (anchor) element.

Once you've done this, hover over your image with your cursor. Your cursor's normal pointer should become the link clicking pointer. The photo is now a link.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="http://www.youtube.com"><img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

### Turn an Image into a Link

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```
