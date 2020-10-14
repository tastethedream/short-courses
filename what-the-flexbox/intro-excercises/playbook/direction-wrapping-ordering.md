# What the flexbox

## intro to flex box - video 2

**1. Flex**

  when the outer container is set to flex it will cover the entire width of the screen available.

  Any elements inside the container, divs etc will automatically become flex items.

  Its always best to set the height of the container to avoid worrying about each element within.

**2. inline-flex**

when the outer container is set to inline flex it will cover the width of the content only.

## Working with flex-direction - video 3

**1. Flex-direction: row;**

This is the default! inside elements will span beside each other and stretch vertically to the height you set for the container (or just the height of the content if you have not set it independently).

 **Main axis**

From left to right

**Cross axis**

From top to bottom


**2.  Flex-direction: column;**

This will stack the elements verically on top of one another

 **Main axis**

 From top to bottom

**Cross axis**

From left to right

**3. Flex-direction: row-reverse;**

shows content reversed

**main axis**

from right to left

**4. Flex-direction: column-reverse;**

shows content reversed

**main axis**

from bottom to top

## Wrapping Elements - video 4

**flex-wrap: nowrap**

Is the default

**flex-wrap: wrap**

 **Main axis**

From left to right

**Cross axis**

From top to bottom

will display items like a grid 


**flex-wrap: wrap-reverse**

 **Main axis**

From right to left

**Cross axis**

From bottom to top

will display items like a grid 


if you give the items a width ot 3.333333% you will get equally spaced rows of 3.

If you change direction to column thew column will split when it runs out of space (if you specified the height) If no height specified one column all the way down will be displayed.

Margins are not part of the box model but to create you can use calc

```
.box {
  width: calc(33.3333% - 20px);
}
```

will give a 10px margin each side of each item. Borders and padding behave as normal

## Reordering items

A way to move the order of the DOM elements

`flex:1` will ditribute all items in the container evenly across the screen

**order**

```
.box3 (
  order: 1;
)
```
default order is always 0 unless specified in the container so all the items are at 0. When ordering box 3 for example and giving it order one the boxes will display as follows:-

>1 2 4 5 6 7 8 9 10 3 

you may order with negative numbers for example

```
.box3 (
  order: -1;
)
```


>3 1 2 4 5 6 7 8 9 10

This can affect your selector so do not use this when users may want to copy text etc.








