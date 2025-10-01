1. flipping hair coin 3 times wht are the ods of getting exactly 2 heads HHH, HHT, HTH, THH, TTH, THT, HTT, TTT, 3/8
    
2. suppose you see the first flip is heads, what is the updated probablity of getting exactly two heads among the three flips? H | TH HT TT HH 2/4=1/2
    
3. suppose you cant observe the experiment directly but are told that there were two heads in total. what is your updated assessment of the probblity that the first flip was heads? 2/3
    

sample space = set of all possible outcomes S

so S = {HHH, HHT, HTH, THH, TTH, THT, HTT, TTT} S is the sample space ( )

s ∈ S are outcomes , while we call A ⊂ S events ![[Pasted image 20250929144315.png]] We consider a funciton P : {A ⊂S } -> [0,1] which assisgns to each event A the probablitiy P(A) that it occurs

P satisfies some natural properities like P(A⊔B) = P(A) + P(B) just as we assumed in our calculation to answer q 1 P(A)=3/8 P(THH ⊔HTH⊔HHT)= P(THH)+P(HTH)+P(HHT)= 1/8+1/8+1/8 = 3/8


## lecture 2 
formal axioms of prob theory
1. A set S of possible outcomes, called the sample space.
	- An element s ∈ S is called an outcome of the experiment.
	- A subset A ⊂ S of the possible outcomes, is called an event.
		The set of possible events A ⊂ S is denoted P(S) = {A ⊆ S}.
The event A occurs when it contains the random outcome s ∈ S.


2. A function P : P(S) → [0, 1], written P(A) = P(s ∈ A),
assigning to each A ⊂ S, called an event, a number 0 ≤ P(A) ≤ 1,
which is the probability that the outcome s ∈ A ⊂ S, such that:
	1) P(S) = 1
			
	2) P(A ∪ B) = P(A) + P(B) if A ∩ B = ∅,
		one happened or the other happened, the probablitiy of a or b happening is the probablity of a + prob of b happening as long as there are no element in both a & b. (main rule we need)
	3) P(A1 ∪A2 ∪...) = P(A1) + P(A2) + ... if Ai ∩Aj = ∅ for i ̸= j.
			if we have a very long/inf list of this or this or this happening, its the sum of prob of a, prob of b, ... as long as Ai ∩ Aj doesnt intersect
			

A set might be S, and objects might be s or s1, s2 etc

s ∈ S means the object is is in the collectio S 

S = {s ∈ S} or S = {s1,s2,s3...,sn} 
- note that a set can have inf many elements or none
