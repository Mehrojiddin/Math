# Math
# The Math Object
Unlike other objects, the Math object has no constructor.

The Math object is static.

All methods and properties can be used without creating a Math object first.

# Math Properties (Constants)

The syntax for any Math property is : Math.property.

JavaScript provides 8 mathematical constants that can be accessed as Math properties:

# Math Methods
The syntax for Math any methods is : Math.method(number)

## Number to Integer
There are 4 common methods to round a number to an integer:

Math.round(x)	Returns x rounded to its nearest integer
Math.ceil(x)	Returns x rounded up to its nearest integer
Math.floor(x)	Returns x rounded down to its nearest integer
Math.trunc(x)	Returns the integer part of x (new in ES6)
## Math.round()
Math.round(x) returns the nearest integer:

## Math.ceil()
Math.ceil(x) returns the value of x rounded up to its nearest integer:

## Math.floor()
Math.floor(x) returns the value of x rounded down to its nearest integer:

## Math.trunc()
Math.trunc(x) returns the integer part of x:

## Math.sign()
Math.sign(x) returns if x is negative, null or positive:

## Math.pow()
Math.pow(x, y) returns the value of x to the power of y:

## Math.sqrt()
Math.sqrt(x) returns the square root of x:

## Math.abs()
Math.abs(x) returns the absolute (positive) value of x:

## Math.sin()
Math.sin(x) returns the sine (a value between -1 and 1) of the angle x (given in radians).

If you want to use degrees instead of radians, you have to convert degrees to radians:

Angle in radians = Angle in degrees x PI / 180.


## Math.cos()
Math.cos(x) returns the cosine (a value between -1 and 1) of the angle x (given in radians).

If you want to use degrees instead of radians, you have to convert degrees to radians:

Angle in radians = Angle in degrees x PI / 180.


## Math.min() and Math.max()
Math.min() and Math.max() can be used to find the lowest or highest value in a list of arguments:


## Math.random()
Math.random() returns a random number between 0 (inclusive), and 1 (exclusive):