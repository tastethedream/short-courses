# What the flexbox

## Flexbox alignment and centering with justify-content - video 6

### Justify-content

- How the items aligned along the main axis

- `flex-start` is the default and begins at the left hand side of the container

- `flex-end` begins at the right hand side of the container

- `flex-center` will align the items in the centre of the container without margins

- `space-between` first item will be at `flex start` and the last item will be at `flex end` and the rest will be evenly spaced with eqaul space between


![flexbox space between](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/space-between.PNG "Space between")


- `space-around` first item will be at `flex start` and the last item will be at `flex end` and the rest will be evenly spaced with equal space between but will also give space at the left and right margins

![flexbox space around](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/space-around.png "Space around")


if you change the direction to `flex: column;` you need to add a min height to the container to get the space

![flexbox space around column](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/spacearound-column.png "Space around column")


##  Flexbox alignment and centering with align-items - video 7

- `align-items` is mainly concerned with the cross axis

- you must specify a height for this to vertically centre

- default is `align-items: stretch`

- `align-items: flex-start;` and `flex-end` will behave as normal

- `align-items: baseline;` will make make sure the bottom of each text item is aligned properly even when the items themselves are differing sizes

![flexbox align-items](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/align-items.png "align items")

changing the direction to colum will again switch the axis

## Alignment and centering with align-content -video 8

- `align-content` deals with the white space 

- takes the same parameters as align-items

- Only works when there is extra space on the vertical axis so the item needs a width and the container will need wrapping `flex-wrap: wrap;`

- default is `align-content: stretch`

![flexbox align-content](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/align-content.png "align content")

- `flex-start` will put the extra space at the bottom of the screen


- `flex-end` will put the extra space at the top of the screen


- `space-between` will put the extra space equally between each row

- `space-around` will put the extra space on the top and equally between each row

-`center` will split the space between top and botton and bertically centre the container

## Alignment and centering with align-self - video 9

- `align-self` allows you to taget a specific item and overide the default

- default is `align-content: stretch`

![flexbox align-self](https://github.com/tastethedream/short-courses/blob/what-the-flex-box/images/align-self.png "align self")








