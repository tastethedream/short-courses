# What the flexbox

## Flexbox alignment and centering with justify-content - video 6

### Justify-content

- How the items aligned along the main axis

- `flex-start` is the default and begins at the left hand side of the container

- `flex-end` begins at the right hand side of the container

- `flex-center` will align the items in the centre of the container without margins

- `space-between` first item will be at `flex start` and the last item will be at `flex end` and the rest will be evenly spaced with eqaul space between

![space-between](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/space-between.png"space between")


- `space-around` first item will be at `flex start` and the last item will be at `flex end` and the rest will be evenly spaced with equal space between but will also give space at the left and right margins

![space-between](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/space-around.png"space around")


if you change the direction to `flex: column;` you need to add a min height to the container to get the space

![space-between](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/spacearound-column.png"space around column")


##  Flexbox alignment and centering with align-items - video 7

- `align-items` is mainly concerned with the cross axis

- you must specify a height for this to vertically centre

- default is `align-items: stretch`

- `align-items: flex-start;` and `flex-end` will behave as normal

- `align-items: baseline;` will make make sure the bottom of each text item is aligned properly even when the items themselves are differing sizes

![align-items](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/align-items.png"align items")

changing the direction to colum will again switch the axis



