# The Glue Holding Math Together

By Jeff Hilton

Complex polynomials are an incredibly elegant formulation of the hidden components inherent to other forms of math. They're the glue holding math together. That may sound a tad abstract (which would be true to the complex field's style), but it's a solid intuition for thinking about complex numbers and their usefulness. Most see the complex plane as a sticky substance that gets everywhere and makes you dizzy if you accidentally spend too much time with your nose it. Others huff the stuff on purpose (don't do that). However, a solid respect for and understanding of complex numbers can help you understand why we use complex numbers and and the complex plane to fill in the gaps of mathematics, adhere one form of mathematics to another, and apply it liberally in some of contemporary math's most famous applications.



## Table of Contents

- What you probably remember from grade school

  - For our purposes today, we'll treat the word *function* as synonymous with the word *polynomial*. There are differences in the semantics of the two, but it's close enough for now.
  - So... $f(x) = c_{n}x^{n} + c_{n-1}x^{n-1} + \dots + c_1x + c_0$ or more succinctly, $f(x) = \sum_{i=0}^nc_ix^i$, where $n$ is the number of terms in the polynomial
  - 

### What is a complex number?

Have you ever done something so illegal that the guy putting you in handcuffs is more impressed than disgusted? No? Just me? 

Well shit. There goes the analogy I had planned.

Like cocaine, $i$ is an illegal substance that's too widely used by important people and too widely useful

- what is i?
- a + bi
- Hey, that looks familiar

- What is a complex function?

  - Any function where the input, roots, or coefficients may be complex. Clever naming, I know.
  - ex

- The Fundamental Theorem of Algebra

  - What is it?
    - In a nutshell: 
      - Algebra is "closed with respect to the complex field"
      - All polynomials have exactly the number of roots specified by the polynomial's "highest term" even if they aren't all expressible as real numbers. 
      - All roots of any given polynomial can be expressed as elements in the set of all complex numbers
    - Specifically:
      - (I really need to look this up)
  - What do complex numbers have to do with it?
    - Without complex numbers, there are holes in the solution space of polynomials. Which is kind of bullshit if you ask me--what kind of two-bit operation is God running here, anyway? Why can't I have $3+2i$ watermelons, God? Why did you do this to us?
    - Without complex numbers, not all matrices have eigenvalues and eigenvectors (is this actually true?)
  - The algebraic closure of polynomials in the complex field
    - closed under addition
    - closed under multiplication
  - Why is it important?
    - In quantum physics
    - In computing
    - In algorithms development
      - Complex numbers "complete" math. Problems that are difficult to solve within the constraints of the real numbers often become much simpler to express and solve when allowing for complex numbers. This makes working in the complex field a specialized, but distinctly useful tool in your algorithms toolbelt (I keep mine beside recursion, vectorization, and tree data structures)

- The f$re^{(i\theta)}$nd we'll make along the way

  - What is the natural exponent?
  - Why do we give a shit about it?
    - two important quirks
      - $e$ is $e$'s derivative, and $e$ is $e$'s integral
      - $sin$ and $cos$ mimic only a fraction of $e$'s power. Literally: $re^{(i\theta)} = r(sin^2(\theta) + cos^2(\theta))$
  - Why is it so useful when combined with complex numbers
    - The natural exponent in combination with imaginary numbers gives us powerful little function for translating harder math into easier math. They suck-up mathematical complexity like a binary black-hole system.

- The Complex Field: An Elegant Formulation of Geometric Transformations

  - Complex Fields and Complex Numbers as a Coordinate System
    - Translation
    - Scaling
    - Rotation (exponentiation)
  - Higher Dimensional Geometries
    - The fundamental trade-off: high dimensionality at the cost of mathematical expressiveness
  - Why is it important?
    - In quantum physics
    - In computing
    - In algorithms development

- Squaring up

  - Quantum Physics is about probability waves
  - probability waves aren't probabilities
  - squared probability wave amplitudes are probabilities (duh)
  - What the hell that actually means
    - (I don't know either)

- What kind of qubit operation is God running here, anyway?

  - What are qubits?
  - Why are qubits?
  - Why the fuck do we use such esoteric notation for qubits?
    - I honestly don't know. I'mma find out

  






$$
a+bi
$$





$$
re^{(i\theta)} = r(sin(\theta) + cos(\theta))
$$

