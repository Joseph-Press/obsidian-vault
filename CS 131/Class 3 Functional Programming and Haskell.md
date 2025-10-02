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

### Pure Function
(AKA a Referentially Transparent func)

A function that has two properties:
1) Given a specific input x, the function always returns the same output y.
2) It computes its output exclusively based on its input parameters, without relying on or modifying external data that might change from call to call.

pure: 
```
int f(int p) {

 int q = 5*p*p;

 return q;

}
```

impure:
```
int z; 

int f(int p) {

  return p*z++;

}
```

why?
- They make code easier to reason about, debug and test!
- They enable parallelism and compiler optimizations!
- They help us formally analyze and prove things about programs!

## imperative vs funcitonal
imperative: 
- Algorithmic – series of statements and variable changes.

- Changes in variable state are required.

- Sequences of statements, loops and function calls.

- Multi-threading is tricky and prone to bugs


- The order code executes is important.

functional:
- Transformation through function calls.

- All "variables" are constants - no changes are allowed!

- Function calls and recursion – no loops, no statements! 
	- Another way of saying this is that FP computes with functions rather than recipes of sequential steps.

- Multi-threading is easy!

- The order of execution is of low importance! 