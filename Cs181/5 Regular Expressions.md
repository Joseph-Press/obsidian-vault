
## 5.1 Basic Notions

Def. 
A reg exp is 
- ∅
- {ε}
- {σ}
- `(R^*)`
- (R1, ∪ R2)
- (R1∘R2)

draw sigmas big and epsilons small 


all the ones in para where R1 R1, R2 are reg exp's 
![[IMG_9979.jpg]]



### shorthand 

R^k
= R ∘R∘R∘...R 
k times 

R^t
= R ∘ `(R^*)`

Σ = alphabet 

may  omit {}, (), ∘

precedence, `*` ∘ ∪

![[IMG_9981.jpg]]

![[IMG_9982.jpg]]

ex (0 ∪ ε) `1^*` = `01^* ∪ 1^*`

`1* ∅`=  ∅

 ∅* = ε

(0  ∪ ε)(1 ∪ ε) = ε ∪ Σ ∪∘1

## 5.2 equivalence with automata

thm the lanaugage of every RE is regular 

Pf 

reg langs
- ∅ 
- {ε}
- {J} - not sure it's a j 

reg langs whenver  r1 r1, r2 regular 
- (R1, ∪ R2)
- (R1∘R2)
- `(R^*)`


thm the lang of every NFA can be rep'd by a RF 

Pf given NFA 
1)
![[Drawing 2025-04-16 15.44.16.excalidraw]]
2)
![[Drawing 2025-04-16 15.46.19.excalidraw]]

3) ![[Drawing 2025-04-16 15.51.24.excalidraw]]
into ![[Drawing 2025-04-16 15.53.24.excalidraw]]

![[IMG_9983.jpg]]