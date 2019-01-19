CSS Notes
=========

Position
---------

Example: [JSBin](https://jsbin.com/fasurihesa/edit?html,css,output)

Absolute Positioning - position: absolute;

* Position is relative to a reference element

* The reference element is the nearest positioned ancestor.

* If there is no positioned ancestor it uses the viewport as the reference element. (In this case it would be identical to Position: Fixed;).

* A "Positioned" element is one whose position is anything except static. (This is important, because absolute will ignore the parent element unless it is "positioned" which is sometimes hard to figure out)

BEM Methodology
---------------

[Reference Link](http://getbem.com/introduction)

Core Concepts:

* Block, Element, Modifier

Units
-----

[Reference Link](https://codepen.io/team/MedTouch/pen/YqBJzv)

* px
  * Pixels
  * Related to the Viewport by size in pixels.
  * If Viewport is 800x800 then 8px is 1%
* em
  * M width (in oldschool typography)
  * Related to the font-size of the nearest parent element
* rem
  * Root EM
  * Related to the root font-size. (font-size determined in the html element. 16px default)
  * Best practice is make font-size 62.5% (10px) in the html element style. Then 1rem = 10px. 2rem = 20px 1.4rem = 14px
* vw & vh
  * Viewport Width (vw) and Viewport Height (vh)
  * Related to viewport size where 100vw or 100vh are 100% of the width and height respectively.