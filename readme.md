# Why do you need flexbox?

The objective is to learn flexbox with the following tutorial: https://www.youtube.com/watch?v=2yJEkP2y4nY&list=PLM-Y_YQmMEqBxAQxxNW7J7-BTJdj_Ol3F&index=1

## Float work flow

The container stops seeing the content, since it is not found in the document flow.

There are some provisional solutions for this, how to set ``` clear: both ```.


## Clauses

* ```display: flex```: [CONTAINER] flex container
* ```flex-direction```: [CONTAINER] indicates the main axis X or Y. By default is ```row```
* ```flex-wrap: ```: [CONTAINER] indicates whether the contained elements collapse or not
* ```orden:```: [ITEM] indicates a weight on an element. By default is 0
* ```justify-content:```: [CONTAINER] indicates the alignment in a container depending on the main axis
* ```align-content:```: [CONTAINER]
* ```align-items:```: [CONTAINER] indicates the aligment in a container depending on the cross axis
* ```align-self:```: [ITEM] indicaes the aligment in a item, with a diferent aligment on the main axis
* ```flex-grow```: [ITEM] control the excess space.
* ```flex-shrink:```: [ITEM] control the missing space
* ```flex-basic:```: [ITEM]
* ```flex:```: [ITEM] allows indicate grow/shrink/basic in one property


## Sorting CSS properties

The order I use is as follows: 

* _Layout Properties_: (position, float, clear, display)
* _Box Model Properties__ (width, height, margin, padding)
* _Visual Properties__ (color, background, border, box-shadow)
* _Typography Properties_: (font-size, font-family, text-align, text-transform)
* _Misc Properties_: (cursor, overflow, z-index)

## Interesting resources
* Github repo: https://github.com/juanwmedia/flexbox
* Extensive documentation: https://www.w3.org/TR/css-flexbox-1/
* The good part: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
* Video tutorials about this topic: https://flexbox.io/
* Game: http://www.flexboxdefense.com/
* Cheatsheets:
    * https://yoksel.github.io/flex-cheatsheet/
    * http://flexbox.malven.co/
