### FSMminimization
FSMminimization is a software system that allows the simulation of the creation of atomata with two algorithms that are moore's machine and mealy's machine, each one has different process, but its main objective is to find its related and minimum equivalent atomata.

### Definitions 
# Moore's machine:
- A Moore machine can be defined as a 6-tuple { S, S0, Σ, Λ, Λ, T, G } consisting of.
- a finite set of states ( S )
- a start state (also called initial state) S0 which is an element of (S)
- a finite set called the input alphabet ( Σ )
- a finite set called the output alphabet ( Λ )
- a transition function (T : S × Σ → S) mapping a state and an input to the next state
- an output function (G : S → Λ) mapping each state to the output alphabet.
- The number of states in a Moore machine will be greater than or equal to the number of states in the corresponding Mealy Machine.

# Mealy Machine:
- A Mealy machine is a 6-tuple, M=(S, S0, Σ, Λ, T, G):
- S is a finite set of states.
- S0 is an initial state, which is an element of S. S0 ∈ S
- Σ is a finite set, called the input alphabet.
- Λ is a finite set, called the output alphabet.
- T is a function of transitions (T : S × Σ → S).
- G is an output function (G : S : S × Σ → Λ).

# Usage instructions 
## 1. First steps fill in the fields to create the atomata and the algorithm to realize it.
![image](https://user-images.githubusercontent.com/48284856/112785074-ca257780-9018-11eb-831b-e7fa59877845.png).

Note that the input must be separated by ",". 

## 2. Considering the machine you have selected you will see the following: 
- Moore's machine 

![image](https://user-images.githubusercontent.com/48284856/112785617-04dbdf80-901a-11eb-90c9-e0a2b786305d.png).


- Mealy machine 

![image](https://user-images.githubusercontent.com/48284856/112785709-4076a980-901a-11eb-8f76-c0f8cd6611a5.png).


after we have correctly filled our atomata we can continue with the next step.
## 3. Finally to minimize the atomata we only must undir the button "Minimize" and this will show us another box where our atomata will be minimized. 

![image](https://user-images.githubusercontent.com/48284856/112786290-86803d00-901b-11eb-87aa-e8b8bfb2b8a9.png)
