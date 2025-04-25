
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


## 6.4 cont 
![[EC5358DC-652D-45A4-B21D-30DCEA8C2CA0_1_201_a.jpeg]]


![[C024EB5F-872A-4942-BE81-B61BC6E55D22_1_201_a.jpeg]]![[CF6426A1-B239-4A58-BD3C-7C625B51A834_1_201_a.jpeg]]![[CF3B361B-9EBA-4407-AC95-E65C850ECDDB_1_105_c.jpeg]]![[398B74E0-870C-4407-A2E9-39208853F4A8_1_201_a.jpeg]]