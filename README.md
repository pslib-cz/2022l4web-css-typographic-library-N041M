# Grand - Typographycal library
Author: [Ronald Karel Grant](https://github.com/N041M)
## Description
Grand.css is a free library meant to jumpstart your next project. It contains simple means to implement colours, build buttons, flex and much more. The soul pourpose of this project is to help with rapid-prototyping webs.
## Demo site
Link to [Grand.css](https://pslib-cz.github.io/2022l4web-css-typographic-library-N041M) site for preview.
Whole website was built using the modular nature of this CSS file besides minor stylistic changes. 
## Key features
1. semi-complex display flex "module"
2. semi-fully customisible button builder
3. predefined code snippet style
4. simple colour palette
5. height and width presets
6. marging and padding presets
7. simple centering
## List of contents
1. [Implementation](#implementation)
2. [Variables](#variables)
3. [Font Sizes](#font-sizes)
4. [Buttons](#buttons)
5. [Flex](#flex)
6. [Images](#images)
## Implementation
1. Download the [Grand.css](https://github.com/pslib-cz/2022l4web-css-typographic-library-N041M/blob/master/docs/grand.css) file.
2. Add the file inside your IDE to your project.
3. Link Grand.css in the `<head>` section of a HTML where you want to use this project. 
    - It is recomended that files such as CSS resets and projects like this are linked above your own  CSS files. This prevents unwanted overriding.
```html
<link rel="stylesheet" href="grand.css">
```
## Variables
Grand.css has a list of predefined sizes, timings and colours that can be easily edited in the `:root` section inside the CSS file. All variables are stored there for ease managing global changes.
This is a list of all variables inside Grand.css:

<p align="center">
    <img src="/docs/img/carbon/root.png" alt="root" width="400px">
</p>

## Font Sizes
As can be seen in the [variables](#variables) section, Grand.css contains *5 preset sizes*. An example of this in practice can be seen here:

<p>
    <img src="/docs/img/carbon/fontsize.png" alt="font size">
</p>

The CSS it self is devided into individual cells like so:

<p align="center">
    <img src="/docs/img/carbon/fontsizecss.png" alt="font size css" width="400px">
</p>

List of font styles:
1. `font-tiny`
2. `font-small`
3. `font-medium`
4. `font-large`
5. `font-huge`

## Buttons
Buttons are the most customisable aspect of this project. 
You are able to change:
1. colour of the text
2. background colour
3. size of the font
4. border style
5. border radius
6. border colour

Buttons can be implemented like so:
<img src="/docs/img/carbon/button.png" alt="button">

List of button styles:
1. `btn`
2. `border-(colour)`
3. `radius-(size)`
    - `border-1`, `border-2`, `border-3`  -  number represents pixels

See [variables](#variables) for colours and sizes.

## Flex
This part of Grand.css is meant to assist in fast sketching out and implementing of simple layouts.
Grand.css contains:
1. flex row and row reversed
2. flex column and column reversed
3. justify content space around
4. justify content space between
5. flex wrap and no wrap
6. gap presets

Flex can be implemented like this:
<img src="/docs/img/carbon/flex.png" alt="flex">

List of flex styles:
1. `flex-row`
2. `flex-row-rev`
3. `flex-column`
4. `flex-column-rev`
5. `flex-around`
6. `flex-between`
7. `flex-wrap`
8. `flex-nowrap`
9. `gap-(size)`

See [variables](#variables) for sizes.

## Images
Provides simple animation on hover over a `<img>` tag.

<p align="center">
    <img src="/docs/img/carbon/images.png" alt="images" width="400px">
</p>

Images can be implemeted like this:
<img src="/docs/img/carbon/imgexample.png">

List of image styles:
1. `img`

## Colour sets
Grant.css contains only one colour set that is made to highlight code snippets.

`bg-code` changes background colour to light grey and adds border border.

It can be implemented like so:
<img src="/docs/img/carbon/code.png">

List of colour set styles:
1. `bg-code`

## Colours
This project contains a small colour palette, see [variables](#variable) for said colours.

`(colour)` changes colour of text.

`bg-(colour)` changes background colour.

List of colour styles:
1. `(colour)`
2. `bg-(colour)`
3. `border-(colour)`

## Borders
Enables simple and fast modification of border styles.

Border styled:
1. solid
2. dashed
3. dotted
4. double
5. none

Border thickness:
1. default sizes as seen in [variables](#variables)
2. borders ranging from `1px` to `3px`

Border radiuses:
1. default sizes as seen in [variables](#variables)

List of border styles:
1. `border-solid`
2. `border-dashed`
3. `border-dotted`
4. `border-double`
5. `border-none`
6. `border-(size)`
    1. `border-1`, `border-2`, `border-3`
7. `radius-(size)`

## Miscellaneous
Random things that didnt fit anywhere else. Contains width, height, padding, margin and centering.

List of styles:
1. `width-(size)`
2. `height-(size)`
3. `padding-(size)`
4. `margin-(size)`
5. `center-x`
6. `center-y`