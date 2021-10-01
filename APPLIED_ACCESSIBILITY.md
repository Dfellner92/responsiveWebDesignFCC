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

