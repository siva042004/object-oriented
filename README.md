# Object-Methods
```
Number:
intValue():

Usage: Converts the Number object to an int.
Difference: Similar methods exist for other primitive types, such as doubleValue().
longValue():

Usage: Converts the Number object to a long.
Difference: Similar methods exist for other primitive types, such as floatValue().
doubleValue():

Usage: Converts the Number object to a double.
Difference: Returns the numeric value as a double.
byteValue():

Usage: Converts the Number object to a byte.
Difference: Returns the numeric value as a byte.
compareTo(Number anotherNumber):

Usage: Compares two Number objects numerically.
Difference: Returns a negative value if less than, 0 if equal, and positive if greater than.
equals(Object obj):

Usage: Compares the current object with another for equality.
Difference: Returns true if the objects are of the same class and have the same value.
toString():

Usage: Returns a string representation of the Number object.
Difference: Converts the numeric value to a string.
hashCode():

Usage: Returns the hash code for the Number object.
Difference: Used in hash-based collections.
isNaN():

Usage: Checks if the Number object represents "Not-a-Number" (NaN).
Difference: Useful when dealing with floating-point arithmetic.
valueOf(long x):

Usage: Returns a Number object holding the specified long value.
Difference: Similar methods exist for other primitive types.
Math:
abs(double a):

Usage: Returns the absolute value of a double.
Difference: Similar methods exist for other numeric types.
sqrt(double a):

Usage: Returns the square root of a double.
Difference: Works with doubles; use Math.pow for exponentiation.
sin(double a):

Usage: Returns the sine of a double value.
Difference: Similar methods exist for other trigonometric functions.
max(double a, double b):

Usage: Returns the larger of two double values.
Difference: Similar methods exist for other numeric types.
random():

Usage: Returns a random double between 0.0 (inclusive) and 1.0 (exclusive).
Difference: Useful for generating random numbers.
floor(double a):

Usage: Returns the largest integer less than or equal to a double.
Difference: Similar methods exist for ceiling and rounding.
exp(double a):

Usage: Returns the base of the natural logarithm, raised to the power of a double.
Difference: Useful for exponential functions.
log(double a):

Usage: Returns the natural logarithm (base e) of a double.
Difference: Logarithmic functions.
round(float a):

Usage: Rounds a float to the nearest integer.
Difference: Similar methods exist for other numeric types.
toRadians(double angdeg):

Usage: Converts an angle measured in degrees to radians.
Difference: Useful when dealing with trigonometric functions.
String:
length():

Usage: Returns the length of the string.
Difference: Provides the number of characters in the string.
charAt(int index):

Usage: Returns the character at the specified index.
Difference: Allows access to individual characters in the string.
concat(String str):

Usage: Concatenates the specified string to the end of this string.
Difference: Creates a new string with the concatenated values.
equals(Object anObject):

Usage: Compares this string to another object for equality.
Difference: Checks if the content of two strings is the same.
substring(int beginIndex):

Usage: Returns a new string that is a substring of this string.
Difference: Extracts a portion of the original string.
toUpperCase():

Usage: Converts all characters in this string to uppercase.
Difference: Changes the case of alphabetic characters in the string.
toLowerCase():

Usage: Converts all characters in this string to lowercase.
Difference: Changes the case of alphabetic characters in the string.
indexOf(String str):

Usage: Returns the index within this string of the first occurrence of the specified substring.
Difference: Locates the position of a substring in the string.
replace(char oldChar, char newChar):

Usage: Returns a new string resulting from replacing all occurrences of oldChar with newChar.
Difference: Replaces specified characters in the string.
startsWith(String prefix):

Usage: Tests if this string starts with the specified prefix.
Difference: Checks the beginning of the string for a specified sequence.
Array:
length:

Usage: Returns the length of the array.
Difference: Provides the number of elements in the array.
clone():

Usage: Creates and returns a copy of the array.
Difference: Allows creating a new array with the same elements.
toString():

Usage: Returns a string representation of the array.
Difference: Useful for debugging and printing the contents of an array.
copyOfRange(T[] original, int from, int to):

Usage: Copies the specified range of the specified array into a new array.
Difference: Allows copying a specific portion of an array.
fill(T[] a, T val):

Usage: Assigns the specified value to each element of the specified array.
Difference: Useful for initializing or resetting the array.
sort(T[] a):

Usage: Sorts the specified array of objects into ascending order.
Difference: Sorts the elements in their natural order or using a comparator.
binarySearch(T[] a, T key):

Usage: Searches the specified array for the specified object using the binary search algorithm.
Difference: Requires a sorted array for efficient searching.
asList(T... a):

Usage: Returns a fixed-size list backed by the specified array.
Difference: Provides a convenient way to work with arrays as lists.
equals(Object[] a, Object[] a2):
```
