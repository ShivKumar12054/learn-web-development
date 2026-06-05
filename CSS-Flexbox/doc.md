Flexbox:

Display - is the property that decides whether the container that is flexbox container or not
e.g display: flex
- if u set a element as a 'display: flex' then that becomes an container and all childerns will be the flex items

usally flexbox has 2 axis
- main axis
- cross axis

when we apply flex, by default items shown as row style where main axis is horizontel and cross is verticle which is also called as flex-direction by default set to row.


## flex-directtion
- what is flex-direction
    This is the direction on which the flex items are displayed, by default it is from left to right
Values
- default
    it is set to 'row' which the flow direction is from left to right

- row-reverse
    this changes the flow direction to start from other end from main axis i.e right to left (if the flex-direction is 'row')

- column
    this makes the flex-direction to change it's default behaviour i.e from row to coumn, meaning when we change the prop value to column, this is change the items to render column wise, where now top to bottom is main axis and left to right is cross axis (opposite to default behaviour)

- column-reverse
    this changes the flex direction where the first elemenet is started from bottom and ends towards top
    Note: if there is no space and it is going out of bound on 'column-reverse' this will show something like first element starts on edge of container but all after top edge is used all other elements looks like they are behind the top section of the page itself. for other directions i.e right, left and bottom the page can be shown or it just overflows as page grows





## justify-content (main axis navigator)
- what is justify-content ?
    This is what used to displace or place items as one whole thing on a 'main axis'.

Values
- flex-start
    used to keep everything on starting point of main axis
- flex-end
    used to move all items towars end of the main axis
- center
    used to move all flex items to the center part of the main axis
Note: the order of items remain same



## flex-wrap
- what is flex-wrap ?
    used to put the overflown flex items onto new line for the main axis, since the main and cross axis is fixed on a point.

Values
- wrap
    this makes the main axis to go to new line if the flex items are growing out of the flex container
- wrap-reverse


## align-items (cross axis navigator)
- what is align-items ?
    used to displace or change the postion of flex items (as a whole) on the cross axis

values
- flex-start
    used to keep the all flex items towards the start of the cross axis.
- flex-end
    used to keep the all flex items towards the end of the cross axis.
- center
    used to move all flex items to the center part of the cross axis



## align-content
- what is align-content
    used to manage the space between (the columns of flex item if and only they have more than one) the flex items (column or row) when ever and only we have multiple cross axis or cross axis goes onto new lines while using flex-wrap

Values
- flex-start
- flex-end
- center


## flex-basis, flex-grow and flex-shirnk
    All of these target individual flex items to do stuff 💨
## Flex-basis
    - what is flex-basis ?
        determine the initial main size i.e meaning what ever is ther in main axis will be set to this value
        example - if we have display: flex,
            - now the right to left is main axis which is also determine by width
            - if we set the flex-basis: 300px this will change/ override the width to 300px
            - if we have display: column where the main is from top to botton, now the height of that flex items will be increased. easy !!!

## flex-grow
    - didn't really strike me to learn
## flex-shirnk
    - didn't really strike me to learn
