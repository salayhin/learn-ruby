
### upcase
Returns a copy of str with all lowercase letters replaced with their uppercase counterparts.

"hEllO".upcase   #=> "HELLO"

### downcase
One can convert a string to lower case as well. Ruby calls this method downcase. Convert the string below into lower case.
"hEllO".downcase   #=> "hello"

### swapcase
Ruby provides a way to swap the case of every character in it
"ThiS iS A vErY ComPlEx SenTeNcE".swapcase

### map

The map method can be used to create a new array based on the original array, but with the values modified by the supplied block:

arr.map { |a| 2 * a }   #=> [2, 4, 6, 8, 10]
arr                   #=> [1, 2, 3, 4, 5]
arr.map! { |a| a**2 } #=> [1, 4, 9, 16, 25]
arr                   #=> [1, 4, 9, 16, 25]


