FLEX(grow or shrink)BOX:
    is a way to arrange items into rows or columns
FLEX CONTAINER
    is any element that has display: flex; property-value
FLEX ITEMS
    is any element that lives inside of a flex container
FLEX CONTAINTER AND FLEX ITEM
    any element can also be a flex container and a flex item



display: flex;          to be declared in the container

flex: 1;                to be declared in flex items
    flex-grow           the flex item's growth factor
    flex-shrink         the flex item's shrink factor
    flex-basis          set's the flex item's initial size: flex-grow and flex-shrink is based on flex-basis
flex: 2;
flex: 1 0 auto;         flex-basis: auto, checks for width declaration

flex: 1;                = flex: 1 1 0;
flex: 2;                = flex: 2 1 0;
flex: auto;             = flex: 1 1 auto;