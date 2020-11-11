# CSS

CSS allows you to create rules that control the way that each individual box is presented.

## Some Example styles include

### Boxes

- width and height

- borders (color, width, style)

- background colors and images

- position in browser window

### Text

- typeface

- size

- color

- italics, bold, uppercase

- lowercase, small-caps

## CSS Associates rules with HTML Elements

 CSS rule contains two parts: a selector and a declaration.

`p{'font-family': Arial;}` The `p` is the selector while the rest is the declaration.

## CSS Properties affect how elements are displayed

CSS declarations sit insde curly brackets and are also made of two parts: a property and a value, separated by a colon. you can use several properties in one declaration, separated by a semi-colon.

`h1, h2, h3 {
    font-family: Arial;
    color: yellow;
}` In this case, the `font-family` and `color` are the properties, while the things that specify what they are, are the values.

## CSS can be used internally or externally

Css can be used internally right in the html code on a page using the `<style>` tag, or it can be used on an external style sheet that the html page links to.

## CSS Selectors

Many common selectors in CSS are as follows below. They determine what the style applies to.

- `* {}` universal selector targets all elements

- ` h1, h2, h3 {}` targets heading tags 

- `.note {}` targets and element whose class attribute has a value of note

- `p.note {}` targets only `<p>` elements with class attribute of note

- `#introduction {}` targets element whose id attribute has a value of introduction

- `li>a {}` targets any `<a>` elements that are children of an `<li>` element but not other `<a>` elements on the page

- `p a {}` targets any `<a>` elements that are insdide a `<p>` element

- `h1+p {}` targets first `<p>` element after any `<h1>` element but not other `<p>` elements

- `h1~p {}` If you had any two `<p>` elements that are siblings of an `<h1>` element, this rule would apply to both

## CSS Importance and Inheritance

### CSS Importance

The closest and most specific rule that applies is the one that takes presedence. You can add `!` after any property value to declare that rule to be important.

### CSS Inheritance

You can specify the font-family or color on the `<body>` element, they will apply to most child elements. This does not work with background-color as that would get messy. However, you can make things inherit by using `inherit` in the value.

## CSS Color

Every color on a computer screen is made my mixing red, green, and blue. You can adjust foregorund color, and background color.  you can adjust hue, saturation, brightness, contrast. Css color can be picked with rgba, hex codes, hsl, and hsla.

## Opacity

Opacity is how see through something is. You can do cool things with this on a web page like making the wrapper see through with a background image that stays centered viewing window.

[back to README](README.md)