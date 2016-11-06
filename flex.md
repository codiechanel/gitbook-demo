# Flex

## FlexDirection 

By default, FlexDirection is set to 'column'. This displays child views like a list.

Each child would then take up the entire row if width is not specified.

If FlexDirection is set to 'row', each child view will take up all vertical space.


## Consuming available space

If your view is a container, you normally set ```flex: 1``` so you get all the remaining space in both directions.


## justifyContent


This property will depend on the FlexDirection. If you want your child views to gravitate towards the end, you can use:

```justifyContent: 'flex-end'```
 

## alignItems

 
 alignItems is very similiar to justifyContent, except that it works on the opposite axis.
 

## space-around

Divides your child views evenly. So if you have two child views for example, each view will get 50% of the screen.
## space-between
It will divide the container by the number of child views, and fill that space.
## alignSelf
alignSelf works on the view itself not on its child views.