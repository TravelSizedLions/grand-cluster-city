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
  - [connection] Holy crap, solutions for this can be modeled as finite state automata or a k-complete weighted directed graph! And we can drop either the zero-cost edges or non-zero edges to create the graph representations of each transformation set! Which means this is mappable to existing graph traversal and path optimization algorithms like A*!
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
- [connection] Sounds like she's going to use this formulation to point back to quantum entanglement's role in updated thermodynamics. Entanglement is a connection, after all. My prediction: interference operations can be used to create constructive patterns that effectively control the flow of heat from one system to another. Nuts!
- Ex: If there's a fridge, opening the fridge will let warmth in, and to keep the fridge cold, we need to do Work (reliable energy) to keep the warmth out - It's "expenditure of a work resource"
- Odd note: mentions that the exchange of heat "gives us the sense time has passed"

What's it mean to have temperature?
- Suppose you measure a system's energy $\rarr$ outcome is random
- Probability of a certain outcome $E$: $p(E) \propto exp\big(-\dfrac{E}{k_BT}\big)$
  - $k_B$ - Boltzman's constant
  - $T$ - Temperature
- Quick sidebar with Blizz
  - the negative acts like a flip for the exponentiation. High values of E are exponentially unlikely
  - the denominator controls the rate of change for the exponentiation. High values of E with high temperature are as likely as low values of E with low temperatures
  - Note on temperature: 
    - The common misconception is that Temperature is exactly equivalent to Energy 
    - BUT! It's actually a statistically emergent property of a system, like pressure. High pressure can exist with relatively few particles if the particles are constrained enough. Similarly, high temperatures can exist even with less total energy if the energy is highly concentrated.
    - Ex: A meteor floating through space has a TON of kinetic energy, but low temperatures. Comparatively a boiling cup of water has less kinetic energy than the meteor, but much higher temperature.

27:29
What does it mean for a Quantum System to have a temperature?
- Same thing, but with another condition for coherences
- "Coherences of the state relative to the energy eigenbasis must all vanish" - ...what?
  - Any parts of the system relevant to measuring "quantum temperature" that are in superposition must decohere before temperature even makes sense as a concept.
  - I.E.: Since superposition only works as a concept at the probability amplitude level and temperature is a probabalistic concept, the two ideas are mutually exclusive.

Suppose you have two quantum energy states $E_h$ and $E_c$ possible with temperatures $T_h$ and $T_c$
- Two random quantum states like this can share correlations
- Unlike 2 independent variables: $c_1$ and $c_2$ as two coin flips
- Suppose $p(c_1 = heads) = 1/2$, $p(c_1 = heads) = 1/2$ - same as with $c_2$. No correlation
- Then $p(c_1 = heads, c_2 = heads) = p(c_1 = heads) \times p(c_2 = heads) = \dfrac{1}{4}$ 
- Each pairing of outcomes has the same probability in this case, but the important piece is that the probabilities of all possible outcomes sums to 1.
- _Now_ suppose we have two quantum coins $\tilde{c}_1, \tilde{c}_2$
- $p(\tilde{c}_1 = heads) = 1/2$, $p(\tilde{c}_1 = heads) = 1/2$ and $\tilde{c}_2$'s possible outcomes are the same
- **However!** $p(\tilde{c}_1 = heads, \tilde{c}_2 = heads) = 1/2$, not $1/4$ like normally.
- This means $p(\tilde{c}_1 = \tilde{c}_2) = 1$. Since they're correlated, they can't be different from one another
  - (In _this_ case. If they were entangled when the had opposite states, they'd instead never have the same state while entangled)

- [question] Wait - do entangled particles always have a correlation strength of 1? Is there ever a point when the correlation strength is less than 1, but not 0?
  - [answer]: As it turns out, yes! This is where the ideas of maximally entangled states, partially entangled states, and mixed states comes from
    - Maximally entangled: correlation of 1 - this is the classic "Bell Pair"
    - Partial Entanglement: more correlated than classical particles, but not perfectly correlated
    - Mixed states: when entangled particles interact with their environment, their entanglement with an intended particle leaks away

- [deeper discussion] - so I think Halpern is scratching at a concept that might be noble-prizeworthy: Quantum interactions like entanglement have correlations and other statistical properties. But if that's the case, then it suggests entanglement is an emergent statistical property of a system (just like temperature and pressure), rather than ever actually between just two quantum particles. It's essentially saying: entanglement is a symptom, not the cause. That'd explain why maintaining coherence and fighting decoherence is so difficult. Quantum computing is basically trying to do calculations on the quantum equivalent to warmth rather than more fundemental particle properties like charge.

- [even deeper discussion] - So...what if the emergence of seemingly separate quantum particles entangled together is actually like a mirage? Tht

- Two random variables can share correlations
  - This can encode an informational resource
  - von Neumann entropy: $S(\rho) := -Tr(\rho \log \rho)$