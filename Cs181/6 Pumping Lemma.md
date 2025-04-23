
## 6.1 first nonreg lang 

theorm L = {0^n 1^n ; 1>= 1}
is nonreg

![[IMG_0027.jpg]]


## 6.2 pumping lemma 

lem 
let L be a reg leang. then there is p ∈N s.t every w ∈L of Length >= p can be written as w = xyz
where 
- x,y,z are strings 
- y =/= ε
- |xy|<= p 
- xyz ∈ L for all i = 0, 1,2,...



pf 

![[Drawing 2025-04-21 15.24.22.excalidraw]]

x = part of w before first loop 

y= `~~~~~~~~~inside~~~~~~~~`
z= `~~~~~~~~~after~~~~~~~~`

then 
- w = xyz 
- y =/= ε
- |xy|<= p 
- xyz ∈ L for all i = 0, 1,2,...

q is repeated 

must visit some state at least twice while reading first p symbols 
![[IMG_0029 2.jpg]]

![[IMG_0030 2.jpg]]

![[IMG_0031 2.jpg]]

## 6.4 examples 

ex L = (0^n 1 ^n: n >= 0} 

∀p (for all p)
∃w  ∈ L, |w| >= p 

∀ x,y,z: 
- w = xyz 
- y =/= ε     
- |xy|<= p 
L is non regular 


