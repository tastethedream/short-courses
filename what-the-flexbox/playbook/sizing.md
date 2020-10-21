# What the flexbox

## Understanding Flexbox sizing with flex property - video 10

### Flex property

- Deals with extra or not enough space.

- `flex:1;` each item will take up the exact amount of space regardless of the content within them

- `flex:2;` the targetted item will take up double the amount of space regardless of the content within it


## Finally Understanding Flexbox flex-grow, flex-shrink and flex-basis - video 11

### flex-grow

- How is the extra space divided on the same line?

- `flex-grow: 0;` is the default and will not effect anything even if there is extra room

- `flex-grow: 1;` will take up the remaining space on the line(if there is any)

```
container{
    display: flex;
}

.box1{
    flex-basis: 400px;
    flex-grow: 10;
}

.box2{
    flex-basis: 400px;
    flex-grow: 1;
}
```

will give box one 10 times the extra space than it gives to box 2

- if there is no extra space the items will just become smaller as there is no wrapping added to the items

### flex-shrink

- Deals with the fact that there may not be enough space

- Default is `flex-shrink: 1;` and will just evenly distribute the available space between the items

- `flex-shrink: 10;` will give up 10 times the space in proportion to the other items

- Great for sidebars etc in responsive design

**Short hand `flex: 10 5 400px;` shows grow, shrink and then basis on the one line. you do not have to set the basis**

### flex-basis

 - How wide should each item be

 - `flex-basis: 400px` will make the targeted elements 400px wide


 ## How flexbox's flex-basis and wrapping work together - video 12

 - If you do not stiplulate flex grow or shrink the shrink default of 1 will kick in if there is not enough spaceon one line for your specified flex basis

 -  to make the items spill on to the next line you need `flex: wrap;`

 - If using `flex-dirction: column;` you need to specify `min-height` or `height` to see what happens to the space using grow and shrink

 - Good for grids of images if you want differing sized pictures










