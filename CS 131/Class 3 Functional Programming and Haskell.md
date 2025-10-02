Functional programming is one of the earliest programming paradigms – and LISP was the first functional language.

Haskell is  one of the few pure functional languages, so it's a good language to illustrate key concepts.

## Core functional programming Concepts
1) All functions must take at least one argument and return a value.
	- y = f(x)
2) Functions are just like any other data and can be stored in variables and passed as arguments.
	- f(x) = x + 5
	- y = f         z = g(f)
3) All variables are "immutable" and can not be modified after initialization!

```f(x) {  
      for (i=0; i<x; i++) ...  
    }```
```
(no loops bc can't i++)
4) all functions are pure 
- Calling f(x) with a given x always returns the same value y.
- Functions may not use or modify external mutable state/variables.