py-notes
========

notes to learn python

## String methods:
### split()
```
>>> "hi".split()
["hi"]
```
Turns the string `"hi"` in to a list. 

### isalpha()
If all the characters in a string is alphabetic it returns true, and if it is an alphabetic letter, else it returns false.
```
>>> "a".isalpha()
True
>>> "0".isalpha()
False
```

## Functions:
### list()
creates a list, splits all the letters from a string.
```
>>> list("hi")
["h","i"]`
```

Split the string `"hi"` into a list. 

### enumerate()
Gives every element in a list an index.
```
>>> months= ["jan", "feb", "mars"] 
>>> list(enumerate(months)) 
[(0,"jan"), (1,"feb"),(2,"mars")
```

### lambda
With lambda you can create anonymous functions, functions that are not bound to a name.
```
>>> g = lambda x: x**2
>>> print g(8)
64
```

### max()
Returns the largest item in an iterable or the largest of two or more arguments.
```
>>> max([1,2,3,4])
4
```
### filter()
Goes through the list, runs the lambda function on every element, and if it returns True, the value stays in the list, other wise, it will get excluded.
```
>>> words = ["hej", "hello"]
>>> num = 3
>>> list(filter(lambda word: len(word) >num, words))
["hello"]
```
### map()
Goes through the list, runs the lambda function on every element, and return the list.
```
>>> print(list(map(lambda x: len(x), ["katt"])))
[4]

```

