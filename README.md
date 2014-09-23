py-notes
========

notes to learn python

## String methods:
### split()
```
>>> "hi".split()
["hi"]
```
Turns the string `"hi"` in to a list 

### isalpha()
If all the characters in a string is alphabetic it returns true, and if it is an alphabetic letter, else it returns false.
```
>>> "a".isalpha()
True
>>> "0".isalpha()
False
```
Turns the string `"hi"` in to a list 

## Functions:
### list 
creates a list, splits all the letters from a string.
```
>>> list("hi")
["h","i"]`
```

### enumerate
Gives every element in a list an index.
```
>>> months= ["jan", "feb", "mars"] 
>>> list(enumerate(months)) 
[(0,"jan"), (1,"feb"),(2,"mars")

