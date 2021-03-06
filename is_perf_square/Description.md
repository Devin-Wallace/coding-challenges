is_perfect_square, accepts a number and returns True if it's a perfect square and False if it's not. 
A perfect square is any number which has an integer square root. 
So 25 is a perfect square but 24 is not, 9 is a perfect square but 8 is not, 100 is a perfect square but 1000 is not.

example:
```
>>> is_perfect_square(64)
True
>>> is_perfect_square(65)
False
>>> is_perfect_square(100)
True
>>> is_perfect_square(1000)
False
```
make sure that this function raises a TypeError when an invalid type is given(integers and floats are fine but strings aren't)


Bonus 1

The first bonus is to make sure your function returns False for negative numbers.️
```
>>> is_perfect_square(-1)
False
>>> is_perfect_square(-4)
False
```
Bonus 2

The second bonus is to make sure your function works for really big numbers.️
```
>>> is_perfect_square(4624000000000000)
True
>>> is_perfect_square(4623999999999999)
False
```
