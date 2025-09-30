iobject referencecs, 
- variables names as pointers 
- Names attached to an underlying object which you can modify
- but if you modify what the variable name points to the underlying object remains the same

## Mutability
mutable objects
- lists, dicts, sets
immutable 
- ints, floats, tuples

mutable obejcts can change if you pass them in as a param
immurable objects can contain mutable objects that you can change
a variable name is like a pointer reassignment doesnt affect the object it poitns at. 
for lists += vs + might have unexpected behavior

x=1,
some object 1, so x is pointing to 1, 
x+=1 
x is pointing to a new object, with has 2 inside of it. the 