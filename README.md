# Project Title

This is a sass mixin for people who use BEM structure to generate variants of a certain element based on a sass color profile.

## Use-case:
You have a certain element which you want in a few different variations without copy pasting. Think about changing the background color to another value based on the modifier of the element.

## Example:

You have this structure in html:
```
<div class="section section--primary">
  <h2>Title</h2>
</div>
```

You use it in sass:
```
.section{
  @include give-variants('background-color');
}
```
The 'section' is the element there goes the basic styling like padding etc, the --primary is the modifier of the element which says something about the style of the element (background, color).

