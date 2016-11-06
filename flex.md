# Flex

## FlexDirection 

By default, FlexDirection is set to 'column'. This displays child views like a list.

Each child would then take up the entire row if width is not specified.

If FlexDirection is set to 'row', each child view will take up all vertical space.


## Consuming available space

If your view is a container, you normally set ```flex: 1``` so you get all the remaining space in both directions.


## justifyContent


This property will depend on the FlexDirection. If you want your child to start at the end, you can use:

```justifyContent: 'flex-end'```
 
 hgkk