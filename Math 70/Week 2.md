Example: There’s a big bag of treats with orange and black
wrappers, some are chocolate inside and some are licorice:

|           | Orange | Black | Total |
| --------- | ------ | ----- | ----- |
| Chocolate | 8      | 2     | 10    |
| Liquorice | 5      | 15    | 20    |
| Total     | 13     | 17    | 30    |

Suppose you sample a random treat (or trick!) from the bag:
1. What is the probability that you get a chocolate?
	- P(C) = 1/3 
2. What is prob of chocolate if the candy wrapper is orange?
	- P(C|O) (prob of choco given wrapper is orange) = 8/13
3. Can you write this in terms of prob. of chocolate and orange?
	- P(C∩O)=8/30 = 4/15

## Conditional probability - definition and basic results

Let S be a sample space and A, B ⊂ S be two events.  
The conditional probability of A given B is defined as:

**P(A|B) = P(A ∩ B) / P(B)**

(We assume P(B) ≠ 0.)

This means: the probability that A happens _given_ that B happened  
equals the probability that both A and B happen, divided by the probability that B happens.

### Example (candy bag)

If there are 30 treats and 8 are chocolate with orange wrappers,  
and 13 treats are orange in total, then:

**P(chocolate | orange) = (8/30) / (13/30) = 8/13**

### Some immediate facts

- **P(B|B) = 1**  
    If we already know B happened, then the chance of B is 100%.

- **P(–|B)** acts like a new probability system, but only inside B.


### Multiplication rule
**P(A ∩ B) = P(A|B) × P(B)**

### Chain rule (generalized multiplication)
For three events:

**P(A ∩ B ∩ C) = P(A) × P(B|A) × P(C|A ∩ B)**

For many events A1, A2, ..., An:

**P(A1 ∩ A2 ∩ ... ∩ An) = P(A1) × P(A2|A1) × P(A3|A1 ∩ A2) × ... × P(An|A1 ∩ ... ∩ A(n-1))**

___ 
- **In plain words:**  
    Probability of A given B = “probability of both A and B” divided by “probability of B”.
    
- **Why this is useful:**  
    It helps break down problems step by step.  
    If you want the chance of A _and_ B, find:
    
    1. The chance of B
    2. The chance of A _once B has happened_  
        Then multiply them together.


### Discussion: multiplication rule and conditional expectation
Consider a standard deck of 52 cards, which has 13 of each suit.
Suppose we draw one, two, or three cards from the deck:
1. What is the probability of drawing a heart?
	- 13/52 = 1/4
2. What is the prob. of drawing a heart and then a diamond?
	- `13/52*13/51`
3. What is the prob. of drawing heart then diamond then club?
	- `13/52*13/51*13/50`
4. What is the prob. of drawing three hearts in a row?
	- `13/52*12/51*11/50`
5. What is the prob. of drawing three aces in a row?
	-  `4/52*3/51*2/50`
6. What is the prob. of drawing one ace, one king, and one queen, in any order (still assuming you draw three cards)?
	- `4/52*4/51*4/50`