# CSS Flexbox cheatsheet

A one-stop flexbox reference, maintained in Markdown but prettified and exported to HTML by [Dillinger.io](http://dillinger.io/).

Try the CSS game [Flexbox Defence](http://www.flexboxdefense.com/).

The following CSS rules go inside a flex container, displayed as either a block [`display: flex;`](http://www.w3schools.com/cssref/css3_pr_flex.asp) (the the example at bottom) or inline-block element `display: inline-flex;`.

## `justify-content:`
- `flex-start` group items to left (the start) of container
- `flex-end` group items to right of container
- `center` group items in the center of a container
- `space-between` distribute items so first/last are left/right and the rest equally between
- `space-around` distribute and space items equally

## `align-items:` and `align-self:`
- `flex-start` across top
- `flex-end` across bottom
- `center` in center
- `baseline` across baseline
- `stretch` space items or stretch item to fill

## `flex-direction:`
- `row` left to right
- `row-reverse` right to left
- `column` top to bottom
- `column-reverse` bottom to top

## Example

    .my-class {
      display: flex;
      justify-content: space-around;
      align-items: flex-start;
      flex-direction: column;
    }
