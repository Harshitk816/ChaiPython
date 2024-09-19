# Numbers in-depth in Python:

# math Library:
- To import this library, we use :
`import math`
- This will import all the methods and properties of math library to be used.

### math.floor()
- This method rounds a number downward to the nearest integer.
-  Example usage of math.floor


`number = 4.7`

`floored_number = math.floor(number)
print(floored_number)  # Output: 4`

### math.ceil()

- This method rounds a number upward to the nearest integer.
- Example usage of math.ceil:

`number = 4.3`

`ceiled_number = math.ceil(number)
print(ceiled_number)   # Output: 5`

### math.trunc()

- The math.trunc function truncates a number by removing the decimal part and returning the integer part of the number.
- Here is an example:

`number = 4.7`

`truncated_number = math.trunc(number)
print(truncated_number)  # Output: 4`

# Random Library:
- To import this library, we use :
`import random`

- This will import all the methods and properties of random library to be used.
### random.randint()
- This function returns a random integer in the range [a, b]
- Example usage of random.randint:
`random_number = random.randint(1, 10)`

`print(random_number)  # Output: a random integer between 1 and 10`

### random.uniform()
- This function returns a random floating point number N such that a <= N <= b
- Example usage of random.uniform:

`random_number = random.uniform(1.0, 10.0)`
`print(random_number)  # Output: a random floating point number between 1.0 and 10.0`

### random.choice()
- This function returns a random element from a non-empty sequence.
- Example usage of random.choice:

`fruits = ['apple', 'banana', 'cherry']
random_fruit = random.choice(fruits)
print(random_fruit)  # Output: a random fruit from the list`

### random.shuffle()
- This function shuffles the elements in a list in place.

- Example usage of random.shuffle:

`fruits = ['apple', 'banana', 'cherry']`

`random.shuffle(fruits)
print(fruits) # Output: a shuffled list of fruits`


# Decimal Library

- To import this library, we use :

`from decimal import Decimal`
## Decimal()

- This function returns a Decimal object constructed from the argument string.

- Example usage of Decimal:
`decimal_number = Decimal('3.14159')`
`print(decimal_number)  # Output: a Decimal object representing 3.14159`

# Fraction Library:

- To import this library, we use:


`from fractions import Fraction`

## Fraction()

- This function returns a Fraction object constructed from the argument string.
- Example usage of Fraction:

`fraction_number = Fraction('3/4')`

`print(fraction_number)  # Output: a Fraction object representing 3/4`

# Sets in python:

- Sets are unordered collections of unique elements.

- Sets are defined by placing elements inside curly brackets {} or using the set() function.
- Example usage of sets:

`set1 = {1, 2, 3, 4, 5}`

`set2 = {4, 5, 6, 7, 8}`
- To add elements to a set, we use the add() method or the update() method.
- To remove elements from a set, we use the remove() method or the discard() method.
- To check if an element is in a set, we use the in operator.
- To get the union of two sets, we use the union() method.
- To get the intersection of two sets, we use the intersection() method.
- To get the difference of two sets, we use the difference() method.
- To get the symmetric difference of two sets, we use the symmetric_difference() method.
- Example usage of set methods:

`set1 = {1, 2, 3, 4, 5}`

`set2 = {4, 5, 6, 7, 8}`

`set1.add(9)` # Add 9 to set1

`set1.remove(2)` # Remove 2 from set1

`print(3 in set1)` # Check if 3 is in set1

`print(set1.union(set2))` # Get the union of set1 and set2


## type() in python:
- The type() function returns the type of an object.
- Example usage of type:

`type(True) #Returns 'bool'`

`type(123) #Returns 'int'`

`type(3.14) #Returns 'float'`

`type('hello') #Returns 'str'`

`type([1, 2, 3]) #Returns 'list'`

`type({'a': 1, 'b': 2}) #Returns 'dict'`

`type((1, 2, 3)) #Returns 'tuple'`
- We can use the type() function to check the type of an object before performing operations on it
