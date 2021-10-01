### Add a Text Alternative to Images for Visually Impaired Accessibility

Camper Cat happens to be both a coding ninja and an actual ninja, who is building a website to share his knowledge. The profile picture he wants to use shows his skills and should be appreciated by all site visitors. Add an `alt` attribute in the `img` tag, that explains Camper Cat is doing karate. (The image `src` doesn't link to an actual file, so you should see the `alt` text in the display.)

```html
<img src="doingKarateWow.jpeg" alt="Camper Cat Karate" />
```

### Know When Alt Text Should be Left Blank

Camper Cat has coded a skeleton page for the blog part of his website. He's planning to add a visual break between his two articles with a decorative image of a samurai sword. Add an `alt` attribute to the `img` tag and set it to an empty string. (Note that the image `src` doesn't link to an actual file - don't worry that there are no swords showing in the display.)

```html
<img src="samuraiSwords.jpeg" alt="" />
```

### Use Headings to Show Hierarchical Relationships of Content

Camper Cat wants a page on his site dedicated to becoming a ninja. Help him fix the headings so his markup gives semantic meaning to the content, and shows the proper parent-child relationships of his sections. Change all the `h5` tags to the proper heading level to indicate they are subsections of the `h2` ones. Use `h3` tags for the purpose.

```html
<h1>How to Become a Ninja</h1>
<main>
  <h2>Learn the Art of Moving Stealthily</h2>
  <h3>How to Hide in Plain Sight</h3>
  <h3>How to Climb a Wall</h3>

  <h2>Learn the Art of Battle</h2>
  <h3>How to Strengthen your Body</h3>
  <h3>How to Fight like a Ninja</h3>

  <h2>Learn the Art of Living with Honor</h2>
  <h3>How to Breathe Properly</h3>
  <h3>How to Simplify your Life</h3>
</main>
```

### Jump Straight to the Content Using the main Element

Camper Cat has some big ideas for his ninja weapons page. Help him set up his markup by adding opening and closing `main` tags between the `header` and `footer` (covered in other challenges). Keep the `main` tags empty for now.

```html
<header>
  <h1>Weapons of the Ninja</h1>
</header>
<main></main>
<footer></footer>
```

### Wrap Content in the article Element

Camper Cat used `article` tags to wrap the posts on his blog page, but he forgot to use them around the top one. Change the `div` tag to use an `article` tag instead.

```html
<article>
  <h2>The Garfield Files: Lasagna as Training Fuel?</h2>
  <p>
    The internet is littered with varying opinions on nutritional paradigms,
    from catnip paleo to hairball cleanses. But let's turn our attention to an
    often overlooked fitness fuel, and examine the protein-carb-NOM trifecta
    that is lasagna...
  </p>
</article>
```

### Make Screen Reader Navigation Easier with the header Landmark

Camper Cat is writing some great articles about ninja training, and wants to add a page for them to his site. Change the top `div` that currently contains the `h1` to a `header` tag instead.

```html
<header>
  <h1>Training with Camper Cat</h1>
</header>

<main>
  <section id="stealth">
    <h2>Stealth &amp; Agility Training</h2>
    <article>
      <h3>Climb foliage quickly using a minimum spanning tree approach</h3>
    </article>
    <article><h3>No training is NP-complete without parkour</h3></article>
  </section>
  <section id="combat">
    <h2>Combat Training</h2>
    <article>
      <h3>Dispatch multiple enemies with multithreaded tactics</h3>
    </article>
    <article>
      <h3>Goodbye world: 5 proven ways to knock out an opponent</h3>
    </article>
  </section>
  <section id="weapons">
    <h2>Weapons Training</h2>
    <article>
      <h3>Swords: the best tool to literally divide and conquer</h3>
    </article>
    <article>
      <h3>Breadth-first or depth-first in multi-weapon training?</h3>
    </article>
  </section>
</main>
```

### Make Screen Reader Navigation Easier with the nav Landmark

Camper Cat included navigation links at the top of his training page, but wrapped them in a `div`. Change the `div` to a `nav` tag to improve the accessibility on his page.

```html
<header>
  <h1>Training with Camper Cat</h1>

  <nav>
    <ul>
      <li><a href="#stealth">Stealth &amp; Agility</a></li>
      <li><a href="#combat">Combat</a></li>
      <li><a href="#weapons">Weapons</a></li>
    </ul>
  </nav>
</header>
```

### Make Screen Reader Navigation Easier with the footer Landmark

Camper Cat's training page is making good progress. Change the `div` he used to wrap his copyright information at the bottom of the page to a `footer` element.

```html
<footer>&copy; 2018 Camper Cat</footer>
```

### Improve Accessibility of Audio Content with the audio Element

Time to take a break from Camper Cat and meet fellow camper Zersiax (@zersiax), a champion of accessibility and a screen reader user. To hear a clip of his screen reader in action, add an `audio` element after the `p`. Include the `controls` attribute. Then place a `source` tag inside the `audio` tags with the `src` attribute set to `https://s3.amazonaws.com/freecodecamp/screen-reader.mp3` and `type` attribute set to `"audio/mpeg"`.

```html
<body>
  <header>
    <h1>Real Coding Ninjas</h1>
  </header>
  <main>
    <p>A sound clip of Zersiax's screen reader in action.</p>
    <audio controls>
      <source
        src="https://s3.amazonaws.com/freecodecamp/screen-reader.mp3"
        type="audio/mpeg"
      />
    </audio>
  </main>
</body>
```

### Improve Chart Accessibility with the figure Element

Camper Cat is hard at work creating a stacked bar chart showing the amount of time per week to spend training in stealth, combat, and weapons. Help him structure his page better by changing the `div` tag he used to a `figure` tag, and the `p` tag that surrounds the caption to a `figcaption` tag.

```html
<!-- Only change code below this line -->
<figure>
  <!-- Stacked bar chart will go here -->
  <br />
  <figcaption>
    Breakdown per week of time to spend training in stealth, combat, and
    weapons.
  </figcaption>
</figure>
<!-- Only change code above this line -->
```

### Improve Form Field Accessibility with the label Element

Camper Cat expects a lot of interest in his thoughtful blog posts and wants to include an email sign up form. Add a `for` attribute on the email `label` that matches the `id` on its `input` field.

```html
<section>
  <form>
    <p>Sign up to receive Camper Cat's blog posts by email here!</p>

    <label for="email">Email:</label>
    <input type="text" id="email" name="email" />

    <input type="submit" name="submit" value="Submit" />
  </form>
</section>
```

### Wrap Radio Buttons in a fieldset Element for Better Accessibility

Camper Cat wants information about the ninja level of his users when they sign up for his email list. He's added a set of radio buttons and learned from our last lesson to use `label` tags with `for` attributes for each choice. Go Camper Cat! However, his code still needs some help. Change the `div` tag surrounding the radio buttons to a `fieldset` tag, and change the `p` tag inside it to a `legend`.

```html
<fieldset>
  <legend>What level ninja are you?</legend>
  <input id="newbie" type="radio" name="levels" value="newbie" />
  <label for="newbie">Newbie Kitten</label><br />
  <input id="intermediate" type="radio" name="levels" value="intermediate" />
  <label for="intermediate">Developing Student</label><br />
  <input id="master" type="radio" name="levels" value="master" />
  <label for="master">Master</label>
</fieldset>
```

### Add an Accessible Date Picker

Camper Cat is setting up a Mortal Kombat tournament and wants to ask his competitors to see what date works best. Add an `input` tag with a `type` attribute of `date`, an `id` attribute of `pickdate`, and a `name` attribute of `date`.

```html
<input type="date" id="pickdate" name="date" />
```

### Standardize Times with the HTML5 datetime Attribute

Camper Cat's Mortal Kombat survey results are in! Wrap a `time` tag around the text `Thursday, September 15<sup>th</sup>` and add a `datetime` attribute to it set to `2016-09-15`.

```html
<p>
  Thank you to everyone for responding to Master Camper Cat's survey. The best
  day to host the vaunted Mortal Kombat tournament is
  <time datetime="2016-09-15">Thursday, September 15<sup>th</sup></time
  >. May the best ninja win!
</p>
```

### Make Elements Only Visible to a Screen Reader by Using Custom CSS

Camper Cat created a really cool stacked bar chart for his training page, and put the data into a table for his visually impaired users. The table already has an `sr-only` class, but the CSS rules aren't filled in yet. Give the `position` an `absolute` value, the `left` a `-10000px` value, and the `width` and `height` both `1px` values.

```html
<style>
  .sr-only {
    position: absolute;
    left: -10000;
    width: 1px;
    height: 1px;
    top: auto;
    overflow: hidden;
  }
</style>
```

### Improve Readability with High Contrast Text

Camper Cat's choice of light gray text on a white background for his recent blog post has a 1.5:1 contrast ratio, making it hard to read. Change the `color` of the text from the current gray (`#D3D3D3`) to a darker gray (`#636363`) to improve the contrast ratio to 6:1.

```html
<style>
  body {
    color: #636363;
    background-color: #fff;
  }
</style>
```

### Avoid Colorblindness Issues by Using Sufficient Contrast

Camper Cat is experimenting with using color for his blog text and background, but his current combination of a greenish `background-color` with maroon text `color` has a 2.5:1 contrast ratio. You can easily adjust the lightness of the colors since he declared them using the CSS `hsl()` property (which stands for hue, saturation, lightness) by changing the third argument. Increase the `background-color` lightness value from 35% to 55%, and decrease the `color` lightness value from 20% to 15%. This improves the contrast to 5.9:1.

```html
<style>
  body {
    color: hsl(0, 55%, 15%);
    background-color: hsl(120, 25%, 55%);
  }
</style>
```

### Avoid Colorblindness Issues by Carefully Choosing Colors that Convey Information

Camper Cat is testing different styles for an important button, but the yellow (`#FFFF33`) `background-color` and the green (`#33FF33`) text color are neighboring hues on the color wheel and virtually indistinguishable for some colorblind users. (Their similar lightness also fails the contrast ratio check). Change the text `color` to a dark blue (`#003366`) to solve both problems.

```html
<style>
  button {
    color: #003366;
    background-color: #ffff33;
    font-size: 14px;
    padding: 10px;
  }
</style>
```

### Give Links Meaning by Using Descriptive Link Text

The link text that Camper Cat is using is not very descriptive without the surrounding context. Move the anchor (`a`) tags so they wrap around the text `information about batteries` instead of `Click here`.

```html
<p>
  Felines the world over have been waging war on the most persistent of foes.
  This red nemesis combines both cunning stealth and lightning speed. But chin
  up, fellow fighters, our time for victory may soon be near. Click here for
  <a href="">information about batteries</a>
</p>
```

### Make Links Navigable with HTML Access Keys

Camper Cat wants the links around the two blog article titles to have keyboard shortcuts so his site's users can quickly navigate to the full story. Add an `accesskey` attribute to both links and set the first one to `g` (for Garfield) and the second one to `c` (for Chuck Norris).

```html
<h2><a id="second" href="#" accesskey="c">Is Chuck Norris a Cat Person?</a></h2>
```

### Use tabindex to Add Keyboard Focus to an Element

Camper Cat created a new survey to collect information about his users. He knows input fields automatically get keyboard focus, but he wants to make sure his keyboard users pause at the instructions while tabbing through the items. Add a `tabindex` attribute to the `p` tag and set its value to `0`. Bonus - using `tabindex` also enables the CSS pseudo-class `:focus` to work on the `p` tag.

```html
<p tabindex="0">
  Instructions: Fill in ALL your information then click <b>Submit</b>
</p>
```

### Use tabindex to Specify the Order of Keyboard Focus for Several Elements

Camper Cat has a search field on his Inspirational Quotes page that he plans to position in the upper right corner with CSS. He wants the search `input` and submit `input` form controls to be the first two items in the tab order. Add a `tabindex` attribute set to `1` to the `search` `input`, and a `tabindex` attribute set to `2` to the `submit` `input`.

```html
<input tabindex="1" type="search" name="search" id="search" />
<input tabindex="2" type="submit" name="submit" value="Submit" id="submit" />
```
