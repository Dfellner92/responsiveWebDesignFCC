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

### Use CSS Grid units to Change the Size of Columns and Rows

Make a grid with three columns whose widths are as follows: 1fr, 100px, and 2fr.

```css
.container {
  font-size: 40px;
  width: 100%;
  background: LightGray;
  display: grid;
  /* Only change code below this line */

  grid-template-columns: 1fr 100px 2fr;

  /* Only change code above this line */
  grid-template-rows: 50px 50px;
}
```

### Create a Column Gap Using grid-column-gap

Give the columns in the grid a `20px` gap.

```css
.container {
  font-size: 40px;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  /* Only change code below this line */
  grid-column-gap: 20px;

  /* Only change code above this line */
}
```

### Create a Row Gap using grid-row-gap

Create a gap for the rows that is `5px` tall.

```css
.container {
  font-size: 40px;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  /* Only change code below this line */
  grid-row-gap: 5px;

  /* Only change code above this line */
}
```

### Add Gaps Faster with grid-gap

Use `grid-gap` to introduce a `10px` gap between the rows and `20px` gap between the columns.

```css
.container {
  font-size: 40px;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  /* Only change code below this line */
  grid-gap: 10px 20px;

  /* Only change code above this line */
}
```

###