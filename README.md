# vim-ultisnips-react
Vim  UltiSnips snippets for React using modern ES6 syntax

You must follow the convention: `MyComponent`'s source file is `MyComponent.js` and the test for it is `MyComponent.spec.js` or `MyComponent.test.js` in the same directory. This allows to generate variables and classes

## Snippets r...
Snippets for react components

* `rc` - boilerplate for **R**eact **C**omponent
* `rcf` - boilerplate for **R**eact **C**omponent as pure **F**unction
* `rfdn` - **R**eact.**f**ind**D**OM**N**ode
* rpt... - **P**rop**T**ypes records
  * ``rptr`` - **P**rop**T**ypes.[$1].is**R**equired
  * ``rptar`` - **P**rop**T**ypes.**a**rray.is**R**equired
  * ``rptbr`` - **P**rop**T**ypes.**b**ool.is**R**equired
  * ``rptfr`` - **P**rop**T**ypes.**f**unc.is**R**equired
  * ``rptnr`` - **P**rop**T**ypes.**n**number.is**R**equired
  * ``rptor`` - **P**rop**T**ypes.**o**bject.is**R**equired
  * ``rptsr`` - **P**rop**T**ypes.**s**tring.is**R**equired
  * ``rpter`` - **P**rop**T**ypes.**e**lement.is**R**equired

Other types will be (or won't be) implemented soon. Pull requests are welcome

## Snippets rt...
Snippets for react tests.

* `rtc` - creates test boilerplate for **C**omponent
* `rtr` - TestUtils.**r**enderIntoDocument
* `rtfrdct` - TestUtils.**f**ind**R**endered**D**OM**C**omponentWith**T**ag
* `rtfrdcc` - TestUtils.**f**ind**R**endered**D**OM**C**omponentWith**C**lass
* `rtfrct` - TestUtils.**f**ind**R**endered**C**omponentWith**T**ype
* `rtsrdct` - TestUtils.**s**cry**R**endered**D**OM**C**omponentsWith**T**ag
* `rtsrdcc` - TestUtils.**s**cry**R**endered**D**OM**C**omponentsWith**C**lass
* `rtsrct` - TestUtils.**s**cry**R**endered**C**omponentsWith**T**ype

## Installation
Using Vundle:
```
" install UltiSnips
Plugin 'SirVer/ultisnips'
"let g:UltiSnipsExpandTrigger="<C-J>" "(optional) CTRL-J instead of TAB to avoid conflicts with YCM
Plugin 'alexbyk/vim-ultisnips-react'
```
