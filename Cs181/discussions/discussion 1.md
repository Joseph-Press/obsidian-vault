
w: # of 1's in w == i (mod 3) 

is {w N(w,1) = 3k+1 for some k >= 1}

n(w,1 ) means that when you divide this quantity by 3 theres a remainder of 1 


n(w,1)%3 = 1

| 1   | accepted |
| --- | -------- |
| 11  | rej      |
| 0   | rej      |
| 01  | accepted |
![[Drawing 2025-04-04 12.21.22.excalidraw]]



{ w:1w, regarded as a natural #, is div by 5}

| w   | w1  | cor natural num |
| --- | --- | --------------- |
| ε   | 1   | 1               |
| 0   | 10  | 2               |
| 1   | 11  | 3               |
| 00  | 100 | 4               |
![[Drawing 2025-04-04 12.40.18.excalidraw]]

1w = 3 mod 5 
|w| = 2(1w) +1 
= `2*3 +1 mod 5
= 2 


3)
![[IMG_9873.jpg]]
4)L4 = {w: w+xy for some e.g. (n(1001000,00) = 3)
string x,y such that (s.t) 
N(x,0) = n(y,1)}

001![[IMG_9874.jpg]]




# DFAs are forgetful

show that any dfa w/ n states (say) must visit soem state at least twice when it consumes an input of length >= n 

any dfa M with n states with the property that it accepts some strings must accept infinitely many states 