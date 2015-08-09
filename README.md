# vim-ultisnips-react
Vim  UltiSnips snippets for React using modern ES6 syntax

You must follow the convention: `MyComponent` source file is `MyComponent.js` and test for it is `MyComponent.spec.js` or `MyComponent.test.js` in the same directory. This allows to generate variables and classes

## Snippets r
Snippets for react components

* `rc` - boilerplate for subclass of **C**omponent
* `rfn` - React.findDOMNode
* rpt - **P**rop**T**ypes records
  * ``rptfr`` - **P**rop**T**ypes.**f**unc.is**R**equired
  * ``rptsr`` - **P**rop**T**ypes.**s**tring.is**R**equired
  * ``rptbr`` - **P**rop**T**ypes.**b**ool.is**R**equired

## Snippets rt
Snippets for react tests.
* `rtc` - creates test boilerplate for **C**omponent
* `rtr` - TestUtils.**r**enderIntoDocument
* `rtfct` - TestUtils.**f**indRenderedDOM**C**omponentWith**T**ag
* `rtfn` - TestUtils.**f**indRenderedDOM**C**omponentWith**T**ag

## Installation
Using Vundle:
```
" install UltiSnips
Plugin 'SirVer/ultisnips'
"let g:UltiSnipsExpandTrigger="<C-J>" "(optional) CTRL-J instead of TAB to avoid conflicts with YCM
Plugin 'alexbyk/vim-ultisnips-react'
```
