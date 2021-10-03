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

### Use grid-column to Control Spacing

Make the item with the class `item5` consume the last two columns of the grid.

```css
.item5 {
  background: PaleGreen;
  /* Only change code below this line */
  grid-column: 2 / 4;

  /* Only change code above this line */
}
```

### Use grid-row to Control Spacing

Make the element with the `item5` class consume the last two rows.

```css
.item5 {
  background: PaleGreen;
  grid-column: 2 / 4; /* Only change code below
this line */
  grid-row: 2 / 4; /* Only change code above this line */
}
```

### Align an Item Horizontally using justify-self

Use the `justify-self` property to center the item with the class `item2`.

```css
.item2 {
  background: LightSalmon;
  /* Only change code below this line */
  justify-self: center;

  /* Only change code above this line */
}
```

### Align an Item Vertically using align-self

Align the item with the class `item3` vertically at the `end`.

```css
.item3 {
  background: PaleTurquoise;
  /* Only change code below this line */
  align-self: end;

  /* Only change code above this line */
}
```

### Align All Items Horizontally using justify-items

Use this property to center all our items horizontally.

```css
.container {
  font-size: 40px;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  grid-gap: 10px;
  /* Only change code below this line */
  justify-items: center;

  /* Only change code above this line */
}
```

### Align All Items Vertically using align-items

Use it now to move all the items to the end of each cell.

```css
.container {
  font-size: 40px;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  grid-gap: 10px;
  /* Only change code below this line */
  align-items: end;

  /* Only change code above this line */
}
```

### Divide the Grid Into an Area Template

Change the template so the `footer` area spans the entire bottom row. Defining the areas won't have any visual effect right now. Later, you will make an item use an area to see how it works.

```css
.container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
    grid-template-areas:
    /* Only change code below this line */
      grid-template-areas:
      "header header header"
      "advert content content"
      "footer footer footer";
    /* Only change code above this line */
  }
```

### Place Items in Grid Areas Using the grid-area Property

Place an element with the `item5` class in the `footer` area using the `grid-area` property.

```css
.item5 {
  background: PaleGreen;
  /* Only change code below this line */
  grid-area: footer;

  /* Only change code above this line */
}
```

### Use grid-area Without Creating an Areas Template

Using the `grid-area` property, place the element with `item5` class between the third and fourth horizontal lines and between the first and fourth vertical lines.

```css
.item5 {
  background: PaleGreen;
  /* Only change code below this line */
  grid-area: 3 / 1 / 4 / 4;

  /* Only change code above this line */
}
```

### Reduce Repetition Using the repeat Function

Use `repeat` to remove repetition from the `grid-template-columns` property.

```css
.container {
  font-size: 40px;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  /* Only change code below this line */

  grid-template-columns: repeat(3, 1fr);

  /* Only change code above this line */
  grid-template-rows: 1fr 1fr 1fr;
  grid-gap: 10px;
}
```

### Limit Item Size Using the minmax Function

Using the `minmax` function, replace the `1fr` in the `repeat` function with a column size that has the minimum width of `90px` and the maximum width of `1fr`, and resize the preview panel to see the effect.

```css
.container {
  font-size: 40px;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  /* Only change code below this line */

  grid-template-columns: repeat(3, minmax(90px, 1fr));

  /* Only change code above this line */
  grid-template-rows: 1fr 1fr 1fr;
  grid-gap: 10px;
}
```

### Create Flexible Layouts Using auto-fill

In the first grid, use `auto-fill` with `repeat` to fill the grid with columns that have a minimum width of `60px` and maximum of `1fr`. Then resize the preview to see auto-fill in action.

```css
.container {
  font-size: 40px;
  min-height: 100px;
  width: 100%;
  background: LightGray;
  display: grid;
  /* Only change code below this line */

  grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));

  /* Only change code above this line */
  grid-template-rows: 1fr 1fr 1fr;
  grid-gap: 10px;
}
```

### Create Flexible Layouts Using auto-fit

In the second grid, use `auto-fit` with `repeat` to fill the grid with columns that have a minimum width of `60px` and maximum of `1fr`. Then resize the preview to see the difference.

```css
.container2 {
  font-size: 40px;
  min-height: 100px;
  width: 100%;
  background: Silver;
  display: grid;
  /* Only change code below this line */

  grid-template-columns: repeat(auto-fit, minmax(60px, 1fr));

  /* Only change code above this line */
  grid-template-rows: 1fr 1fr 1fr;
  grid-gap: 10px;
}
```

### Use Media Queries to Create Responsive Layouts

When the viewport width is `400px` or more, make the header area occupy the top row completely and the footer area occupy the bottom row completely.

```css
.container {
  font-size: 1.5em;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 50px auto 1fr auto;
  grid-gap: 10px;
  grid-template-areas:
    "header"
    "advert"
    "content"
    "footer";
}

@media (min-width: 300px) {
  .container {
    grid-template-columns: auto 1fr;
    grid-template-rows: auto 1fr auto;
    grid-template-areas:
      "advert header"
      "advert content"
      "advert footer";
  }
}

@media (min-width: 400px) {
  .container {
    grid-template-areas:
      /* Only change code below this line */
      "header header"
      "advert content"
      "footer footer";
    /* Only change code above this line */
  }
}
```

### Create Grids within Grids

Turn the element with the `item3` class into a grid with two columns with a width of `auto` and `1fr` using `display` and `grid-template-columns`.

```css
.item3 {
  background: PaleTurquoise;
  grid-area: content;
  /* Only change code below this line */
  display: grid;
  grid-template-columns: auto 1fr;

  /* Only change code above this line */
}
```
