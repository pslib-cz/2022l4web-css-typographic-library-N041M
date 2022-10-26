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
    <img src="/docs/img/carbon/root.png" alt="root" height="700px">
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
1. font-tiny
2. font-small
3. font-medium
4. font-large
5. font-huge

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
1. btn
2. border-(colour)
    1. border-1, border-2, border-3 - number represents pixels
3. radius-(size)

See [variables](#variables) for colours and sizes.