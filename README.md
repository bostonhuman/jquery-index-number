# jQuery Index Number

This example demonstrates how jQuery gives an index number to each of the elements in the jQuery selection. The :lt() and :gt() selectors and the .eq() method are used to find elements based on their index numbers. For each of the matching elements, the value of the class attributes are changed.

The :lt() selector is used in the selector to pick list items with an index number less than 2. It removes the value hot from their class attribute.
```
$('li:lt(2)').removeClass('hot');
```
The .eq() method selects the first item using the number 0 because the index numbers start at zero. It adds the value of complete to the class attribute.
```
$('li').eq(0).addClass('complete');
```
## How to run the app locally?

* In your terminal type:
```
git clone https://github.com/bostonhuman/jquery-index-number
```
* Open index-numbers.html to run the app.

