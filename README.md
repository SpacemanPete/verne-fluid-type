# Meet Verne

A fluid typography and spacing system of SASS mixins for impeccably smooth responsive websites. 

Verne is a small collection of SASS mixins that allow you to easily define a smoothly responsive typographic scale and resposive spacing based on device viewport size.

This project was inspired by Mike Riethmuller's talk at CSSCOnf Australia in May 18, 2017, which I came across on [YouTube](https://youtu.be/mAvQUIKtW_Y) and Matej Latin's masterful work on the fundamentals for web typography *Better Typography for a Better Web* ([https://betterwebtype.com/](https://betterwebtype.com/)).

The goal of this project is to enable developers to specify their project specifications regarding typographic scale and size quickly, easily, and allow them to move on and not worry about micromanaging font sizes and breakpoints.

The `fluid-type` mixins allow the developer to set the maximm and minimum viewport sizes, font sizes, and line height for their site, which results in an automatically calculated font-size based on viewport.

Additionally, the `fluid-space` mixin leverages the same autocalculated function to allow the developer to set a whole host of css properties to fluidly resize based on device viewport size, including:
  * margin
  * padding
  * height
  * width
  * grid-gap
  * background-position
  * background-position-x
  * background-position-y
  * background-size
  * top
  * bottom
  * left
  * right

Documentation and testing is very thin at the moment but will be fleshed out as well over the next few weeks.

This project is a very early state but the initial API and functionality is stable for production use, with a number of potential enhancements and refactors over the next few months.

Follow the repo for udpates!


TODO: Add examples of usage out of the box

TODO: Add examples of overiding defaults