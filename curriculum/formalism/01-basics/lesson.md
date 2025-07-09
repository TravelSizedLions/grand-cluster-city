# Getting Comfortable with the Basics

## Overview
This is the bedrock of mathematical notation - the fundamental operations and symbols that appear across every field of mathematics. If you're not comfortable with these, you'll struggle with everything else. But don't worry - these are concepts you learned in middle school. We're just making sure we're all speaking the same notational language.

## Why This Matters
Every advanced mathematical field assumes you're fluent in this basic notation. If you're not comfortable with these fundamentals, you'll get lost in the notation before you can even engage with the concepts. Master these, and you have the foundation for everything else.

## Core Notation

### Variable Naming and Constants

#### Variables
Letters or symbols representing unknown values, parameters, or placeholders in mathematical expressions. They abstractly represent a number that could be filled in to calculate the equation. Sometimes that number is unknown and needs to be solved for. Sometimes it's a placeholder any arbitrary number you can plug into a function. Sometimes it's a famous or extremely common number needed in order to make the equation work.

##### Common Notations
- $x$, $y$, $z$ - Most common for unknowns: $x + 2 = 5$
- $a$, $b$, $c$ - Parameters or constants in equations: $ax + b = 0$
- $f$, $g$, $h$ - Function names: $f(x) = x^2$

##### Common Constants
- $\pi \approx 3.14159...$ - Pi, the ratio of circumference to diameter
- $e \approx 2.71828...$ - Euler's number, the base of natural logarithms
- $i = \sqrt{-1}$ - Imaginary unit, the square root of negative one

### Basic Arithmetic Operations

#### Addition
The fundamental operation of combining quantities. Addition is commutative (order doesn't matter) and associative (grouping doesn't matter).

##### Notations
- $+$ - Universal symbol across all mathematical fields: $a + b$, $2 + 3 = 5$

#### Subtraction
The operation of taking one quantity away from another, or indicating negative values.

##### Notations
- $-$ - Used for both subtraction and negation: $a - b$, $5 - 2 = 3$, $-7$

#### Multiplication
The operation of repeated addition or scaling. Has multiple notation systems depending on context and sophistication level.

##### Notations
- $\times$ - Elementary notation, rarely used in higher math: $3 \times 4 = 12$
- $\cdot$ - Dot notation, common in physics: $3 \cdot 4 = 12$
- $*$ - Programming/calculator notation: $3 * 4 = 12$
- **Implicit multiplication** - Most common in advanced math: $3a$, $xy$, $2(x + 3)$

#### Division
The operation of splitting quantities or finding how many times one quantity fits into another. Different notations have different implications for order of operations.

##### Notations
- $\div$ - Elementary notation, rarely used in higher math: $8 \div 2 = 4$
- $/$ - Fraction slash, common in programming: $8/2 = 4$
- $\frac{a}{b}$ - Fraction notation, most common in advanced math: $\frac{8}{2} = 4$

Advanced math overwhelmingly uses fractional notation because it eliminates ambiguity about order of operations. Consider the famous expression $6/2(3)$. With infix division notation, this could be interpreted as either:
- $\frac{6}{2(3)} = \frac{6}{6} = 1$ (treating $2(3)$ as a single unit in the denominator)
- $\frac{6}{2} \times 3 = 3 \times 3 = 9$ (treating division and multiplication as equal precedence, left to right)

This ambiguity has sparked countless internet debates and even causes different calculators to give different answers! But with fractional notation, there's zero ambiguity - you can see exactly what's in the numerator and what's in the denominator: $\frac{6}{2(3)}$ vs $\frac{6}{2} \times 3$.

#### Grouping and Order of Operations
The system for controlling which operations are performed first in mathematical expressions. Without clear grouping and precedence rules, complex expressions would be ambiguous.

##### Notations
- $( )$ - Parentheses, most common grouping: $(a + b) \times c$, $2(x + 3)$
- $[ ]$ - Brackets, for nested grouping or special meanings: $2[x + 3(y - 1)]$
- $\{ \}$ - Braces, for specialized grouping or set notation: $\{x + y\}$ or $\{1, 2, 3\}$

The standard order of operations (PEMDAS/BODMAS) determines precedence when no grouping symbols are present:
- **P**arentheses/**B**rackets first
- **E**xponents/**O**rders (powers) second
- **M**ultiplication and **D**ivision (left to right)
- **A**ddition and **S**ubtraction (left to right)

Grouping acts as a sort of "override" for the normal flow of operations. It's essentially just saying "do all of these operations first, then move on to stuff outside of the group"

### Exponents and Roots

#### Exponents
The operation of repeated multiplication, indicating how many times a number is multiplied by itself.

##### Notations
- $a^b$ - General exponent notation: $a^n$ = "a to the nth power"
- $a^2$ - Squared: "a squared"
- $a^3$ - Cubed: "a cubed"

#### Roots
The inverse operation of exponentiation, finding what number when raised to a power gives the original number.

##### Notations
- $\sqrt{a}$ - Square root: square root of a
- $\sqrt[3]{a}$ - Cube root: cube root of a
- $\sqrt[n]{a}$ - nth root: nth root of a

### Equality and Inequality

#### Equals
The statement that two mathematical expressions have the same value.

##### Notations
- $=$ - Equality symbol: $x = 5$, $2 + 3 = 5$

#### Not equals
The statement that two mathematical expressions do not have the same value.

##### Notations
- $\neq$ - Not equals symbol: $x \neq 0$

#### Inequalities
Statements about the relative size or ordering of mathematical expressions.

##### Notations
- $<$ - Less than: $x < 5$
- $>$ - Greater than: $x > 0$
- $\leq$ - Less than or equal to: $x \leq 10$
- $\geq$ - Greater than or equal to: $x \geq 0$

### Functions

#### Function notation
A mathematical relationship that assigns exactly one output value for each input value.

##### Notations
- $f(x)$ - Function notation, read as "f of x": $f(x) = x + 1$, $g(y) = y^2$

## Field Signatures
Basic arithmetic appears in **every** mathematical field, but you can identify you're looking at "basic math" when you see:
- Simple variable names ($x$, $y$, $a$, $b$)
- Basic operations without specialized symbols
- Elementary fractions and exponents
- Step-by-step algebraic manipulation

## Translation Tables
These basic operations appear in every field, but with different emphasis:
- **Physics**: Uses $\cdot$ for multiplication, vector notation
- **Programming**: Uses $*$ for multiplication, $**$ for exponents
- **Pure math**: Uses implicit multiplication, fraction notation
- **Statistics**: Uses different variable conventions

## Most Likely Encounters
You'll see basic notation everywhere, but explicit teaching of these symbols typically appears in:
- Elementary and middle school textbooks
- Programming documentation
- Review sections of advanced textbooks
- Calculator manuals

## Next Steps
Once you're comfortable with these basics, you'll be ready to see how different fields build specialized notation on top of these fundamentals. Each field takes these core concepts and adds its own "dialect" of symbols and conventions.