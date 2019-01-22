# CSS Flexbox cheatsheet

These CSS rules go inside a **flex container** (the element *containing the boxes to be aligned*).

The **flex container** can be a [block or an inline-block](http://www.w3schools.com/cssref/css3_pr_flex.asp) element: `display: flex;` or `display: inline-flex;`.

The properties with their possible values are a summary of the most-used:

## `justify-content:` horizontal

- `flex-start` group items to **left** (the start) of container
- `flex-end` group items to **right** of container
- `center` group items in the **center** of a container
- `space-between` **distribute** items: first/last are left/right others are equally between
- `space-around` **distribute** and space items **evenly**

## `align-items:` and `align-self:` vertical

- `flex-start` across top
- `flex-end` across bottom
- `center` in center
- `baseline` across baseline
- `stretch` space items or stretch item to fill

## `flex-direction:` order

- `row` flow left to right
- `row-reverse` flow right to left
- `column` stack top to bottom
- `column-reverse` stack bottom to top

## `flex-wrap:` row wrapping
- `nowrap` default value
- `wrap` wrap below at narrower widths
- `wrap-reverse` reverse rows, keep item order

## Example

```css
.my-class {
  display: flex;
  justify-content: space-around;
  align-items: flex-start;
  flex-direction: column;
}
```

---

## References

- CSS game: [Flexbox Defence](http://www.flexboxdefense.com/)
- [Dive Into Flexbox (Greg Smith)](https://bocoup.com/blog/dive-into-flexbox)
- [A Complete Guide to Flexbox (Chris Coyier)](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CanIuse: see flexbox browser support (IE11 bugs)](http://caniuse.com/#feat=flexbox)

## Source code for this cheatsheet

- [Markdown source code](https://github.com/DaveEveritt/flexbox-cheatsheet)
- [styled HTML](https://daveeveritt.github.io/flexbox-cheatsheet/ "Thanks, Dillinger.io")
