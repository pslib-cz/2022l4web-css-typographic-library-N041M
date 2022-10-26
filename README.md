# Grand - Typographycal library
Author: [Ronald Karel Grant](https://github.com/N041M)
## Description
Grand.css is a free library meant to jumpstart your next project. It contains simple means to implement colours, build buttons, flex and much more. The soul pourpose of this project is to help with rapid-prototyping webs.
## Demo site
Link to [Grand.css](https://pslib-cz.github.io/2022l4web-css-typographic-library-N041M) site for preview.
Whole website was built using the modular nature of this CSS file besides minor stylistic changes. 
## List of contents
1. [Implementation](#implementation)
## Implementation
1. Download the [Grand.css](https://github.com/pslib-cz/2022l4web-css-typographic-library-N041M/blob/master/docs/grand.css) file.
2. Add the file inside your IDE to your project.
3. Link Grand.css in the `<head>` section of a HTML where you want to use this project. 
    1. It is recomended that files such as CSS resets and projects like this are linked above your own  CSS files. This prevents unwanted overriding.
```html
<link rel="stylesheet" href="grand.css">
```
## Variables
Grand.css has a list of predefined sizes, timings and colours that can be easily edited in the `:root` section inside the CSS file. All variables are stored there for ease managing global changes.
This is a list of all variables inside Grand.css:
```css
:root {
    /* typography */
    --font-tiny: 12px;
    --font-small: 18px;
    --font-medium: 24px;
    --font-large: 30px;
    --font-huge: 36px;
    /* sizes */
    --tiny: 5px;
    --small: 10px;
    --medium: 15px;
    --large: 20px;
    --huge: 25px;
    /* timing */
    --shortest: 0.25s;
    --short: 0.5s;
    --standard: 0.75s;
    --long: 1s;
    --longest: 1.25s;
    /* colours */
    --purple: #5500FF;
    --black: #000;
    --white: #fff;
    --red: #FA5353;
    --blue: #459AFD;
    --green: #29F676;
    --yellow: #F0F320;
    --orange: #FF921F;
    --light-grey: #ebebeb;
    --light-grey-code-border: #d1d1d1;
}
```
## Font sizes

