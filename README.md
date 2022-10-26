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
![image](https://carbon.now.sh/?bg=rgba%28171%2C+184%2C+195%2C+1%29&t=vscode&wt=none&l=css&width=463&ds=true&dsyoff=20px&dsblur=68px&wc=true&wa=false&pv=56px&ph=56px&ln=false&fl=1&fm=Hack&fs=14px&lh=133%25&si=false&es=2x&wm=false&code=%253Aroot%2520%257B%250A%2520%2520%2520%2520%252F*%2520typography%2520*%252F%250A%2520%2520%2520%2520--font-tiny%253A%252012px%253B%250A%2520%2520%2520%2520--font-small%253A%252018px%253B%250A%2520%2520%2520%2520--font-medium%253A%252024px%253B%250A%2520%2520%2520%2520--font-large%253A%252030px%253B%250A%2520%2520%2520%2520--font-huge%253A%252036px%253B%250A%2520%2520%250A%2520%2520%2520%2520%252F*%2520sizes%2520*%252F%250A%2520%2520%2520%2520--tiny%253A%25205px%253B%250A%2520%2520%2520%2520--small%253A%252010px%253B%250A%2520%2520%2520%2520--medium%253A%252015px%253B%250A%2520%2520%2520%2520--large%253A%252020px%253B%250A%2520%2520%2520%2520--huge%253A%252025px%253B%250A%2520%2520%250A%2520%2520%2520%2520%252F*%2520timing%2520*%252F%250A%2520%2520%2520%2520--shortest%253A%25200.25s%253B%250A%2520%2520%2520%2520--short%253A%25200.5s%253B%250A%2520%2520%2520%2520--standard%253A%25200.75s%253B%250A%2520%2520%2520%2520--long%253A%25201s%253B%250A%2520%2520%2520%2520--longest%253A%25201.25s%253B%250A%2520%2520%250A%2520%2520%2520%2520%252F*%2520colours%2520*%252F%250A%2520%2520%2520%2520--purple%253A%2520%25235500FF%253B%250A%2520%2520%2520%2520--black%253A%2520%2523000%253B%250A%2520%2520%2520%2520--white%253A%2520%2523fff%253B%250A%2520%2520%2520%2520--red%253A%2520%2523FA5353%253B%250A%2520%2520%2520%2520--blue%253A%2520%2523459AFD%253B%250A%2520%2520%2520%2520--green%253A%2520%252329F676%253B%250A%2520%2520%2520%2520--yellow%253A%2520%2523F0F320%253B%250A%2520%2520%2520%2520--orange%253A%2520%2523FF921F%253B%250A%2520%2520%2520%2520--light-grey%253A%2520%2523ebebeb%253B%250A%2520%2520%2520%2520--light-grey-code-border%253A%2520%2523d1d1d1%253B%250A%257D)
## Font sizes

