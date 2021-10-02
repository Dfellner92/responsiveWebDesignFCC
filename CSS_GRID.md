### Create Your First CSS Grid

Change the display of the div with the `container` class to `grid`.

```html
<style>
  .d1 {
    background: LightSkyBlue;
  }
  .d2 {
    background: LightSalmon;
  }
  .d3 {
    background: PaleTurquoise;
  }
  .d4 {
    background: LightPink;
  }
  .d5 {
    background: PaleGreen;
  }

  .container {
    font-size: 40px;
    width: 100%;
    background: LightGray;
    /* Only change code below this line */
    display: grid;

    /* Only change code above this line */
  }
</style>

<div class="container">
  <div class="d1">1</div>
  <div class="d2">2</div>
  <div class="d3">3</div>
  <div class="d4">4</div>
  <div class="d5">5</div>
</div>
```

### Add Columns with grid-template-columns

Give the grid container three columns that are each `100px` wide.

```css
.container {
  font-size: 40px;
  width: 100%;
  background: LightGray;
  display: grid;
  /* Only change code below this line */
  grid-template-columns: 100px;

  /* Only change code above this line */
}
```

### Give the grid container three columns that are each 100px wide.

```css
.container {
  font-size: 40px;
  width: 100%;
  background: LightGray;
  display: grid;
  /* Only change code below this line */
  grid-template-columns: 100px 100px 100px;

  /* Only change code above this line */
}
```

### Add Rows with grid-template-rows

Add two rows to the grid that are `50px` tall each.

```css
.container {
  font-size: 40px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 100px 100px 100px; /* Only change code below this line */
  grid-template-rows: 50px 50px; /* Only change code above this line */
}
```

###