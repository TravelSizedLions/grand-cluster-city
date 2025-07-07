Notes on [Nicole Yunger Halpern - "Updates to the Second Law from Quantum Thermodynamics"](https://www.youtube.com/watch?v=6l_dwS_ty5Q&list=PPSV)

## Where it Started

The traditional law of thermodynamics has a starting point that's based off of boltzman entropy calculations

So basically:
- When predicting the likelihood of macrostates of entropic systems (as is needed for thermodynamics), we use the sum of the negative log probabilities of the possible microstates that can comprise that macrostate.
- That causes issues at a quantum scale:
  - This formulation assumes the systems are at rest (which is never true in quantum systems)

## Thermodynamic Resource Theory
This seems to be a generalization of the concept of entropy

Simplify the goal: Determine what can happen for free, and what requires the use of limited resources to achieve.

In other words: How do we identify what can be achieved _without_ increasing entropy, and what requires an increase in entropy to achieve?

- Environment: in equilibrium at fixed temperature
- Free operations happen in 3 steps:
  1. A piece of the environment $E$ contacts the system of interest $S$
  2. The Environment and System of interest can interact in any way that conserves their total energy (ie, obeys the 1st law of thermodynamics)
  3. $E$ loses contact with $S$, stopping the interaction

- Basic question of the second law:
  - Which states $\ro$ can transform into state $\sigma$ for free? 
  - Which states can $\ro$ not transform into $\sigma$ for free?
  - Connection! Holy crap, solutions for this can be modeled as finite state automata or a k-complete weighted directed graph! And we can drop either the zero-cost edges or non-zero edges to create the graph representations of each transformation set! Which means this is mappable to existing graph traversal and path optimization algorithms like A*!
  - These questions are also general:
    - Don't need to start or end in an equilibrium
    - The system $S$ doesn't need to be a group of classical particles. It can be quantum, or even quasi-classical
    - The system $S$ can be of any size (doesn't have to stick to the typical range for thermodynamics)
  But this generalization comes with a cost:
    - The original second law only requires comparing one inequality to determine which transformations are free
    - This formulation requires checking an entire family of inequalities
      - one set of probability inequalities
      - one set of coherences
      - the math behind this is called "majorization" which has ties to economic theory to understand wealth inequality distributions
  - This formulation is well studied and established, with dates of landmark papers ranging from 2018 all the way back to 1998
  - Points back to her book Quantum Steampunk (this stuff is apparently explained more in CH. 11, lol)

Apparently, correlations (like entanglement), can be used to push heat, on average, from cold to hot, appearing to break entropy


24:38
Another Formulation: Clausius formulation
- Heat can't pass from a colder body to a warmer body (on average) without some other change, _*connected therewith*_, occurring at the same time
- Connection! Sounds like she's going to use this formulation to point back to quantum entanglement's role in updated thermodynamics. Entanglement is a connection, after all. My prediction: interference operations can be used to create constructive patterns that effectively control the flow of heat from one system to another. Nuts!

