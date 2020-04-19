#Array Methods - what to look out for

To avoid confusion upfront - lets define the two key items here.

  - "arr" will be used to reference to any type of array that is created, regardless of its content.
    i.e. [1,2,3,4,5] or ['a','b','c','d'] or [[1,2,3,],[1,2,3]]
  - "Array" references to the internal JavaScript object.



## Getting straight forward information about your array objects.

arr.length - to get the total number of indexes used in the array

Array.isArray(arr) - to confirm if a variable is an Array (Arrays are always typeof Object and need further type definition)

typeof array === 'object'

array instanceof Array === '[object Array]'


## Creating new arrays

simple a = [];

using Array object  b = new Array();

using 