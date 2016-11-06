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
This is basically an override for the settings used by the parent view. ```Stretch``` is the default.
```AlignSelf``` works on the view itself not on its child views. This is really useful, if each view would want to gravitate differently.
```
alignSelf: 'baseline'
```

The view will no longer take up the remaining space, but instead will be contrained based on its content 
```
auto
```
I still need to do some test for this