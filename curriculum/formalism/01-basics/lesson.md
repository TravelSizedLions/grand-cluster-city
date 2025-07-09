# Getting Comfortable with the Basics

## Overview
This is the bedrock of mathematical notation - the fundamental operations and symbols that appear across every field of mathematics. If you're not comfortable with these, you'll struggle with everything else. But don't worry - these are concepts you learned in middle school. We're just making sure we're all speaking the same notational language.

## Core Notation Elements

### Basic Arithmetic Operations
**Addition**: $+$
- Universal symbol across all fields
- Example: $a + b$, $2 + 3 = 5$

**Subtraction**: $-$
- Also used for negation: $-x$ means "negative x"
- Example: $a - b$, $5 - 2 = 3$, $-7$

**Multiplication**: Multiple notations!
- $\times$ - elementary notation, rarely used in higher math
- $\cdot$ - dot notation, common in physics and some fields
- $*$ - programming/calculator notation
- **Implicit multiplication** - $ab$ means $a \times b$ (most common in advanced math)
- Example: $3 \times 4$, $3 \cdot 4$, $3 * 4$, $3a$, $xy$

**Division**: Multiple notations!
- $\div$ - elementary notation, rarely used in higher math
- $/$ - fraction slash, common in programming
- **Fraction notation** - $\frac{a}{b}$ (most common in advanced math)
- Example: $8 \div 2$, $8/2$, $\frac{8}{2}$

Advanced math overwhelmingly uses fractional notation because it eliminates ambiguity about order of operations. Consider the famous expression $6/2(3)$. With infix division notation, this could be interpreted as either:
- $\frac{6}{2(3)} = \frac{6}{6} = 1$ (treating $2(3)$ as a single unit in the denominator)
- $\frac{6}{2} \times 3 = 3 \times 3 = 9$ (treating division and multiplication as equal precedence, left to right)

This ambiguity has sparked countless internet debates and even causes different calculators to give different answers! But with fractional notation, there's zero ambiguity - you can see exactly what's in the numerator and what's in the denominator: $\frac{6}{2(3)}$ vs $\frac{6}{2} \times 3$.

### Grouping and Order of Operations
**Parentheses**: $( )$
- Override natural order of operations
- Example: $(a + b) \times c$, $2(x + 3)$

**Brackets**: $[ ]$
- Often used for inner grouping or special meanings
- Example: $2[x + 3(y - 1)]$

**Braces**: $\{ \}$
- Less common for grouping, more for sets
- Example: $\{x + y\}$ or $\{1, 2, 3\}$

**Order of Operations**: PEMDAS/BODMAS
- **P**arentheses/**B**rackets first
- **E**xponents/**O**rders (powers) second
- **M**ultiplication and **D**ivision (left to right)
- **A**ddition and **S**ubtraction (left to right)

### Exponents and Roots
**Exponents**: $a^b$ or $a^2$
- $a^2$ = "a squared"
- $a^3$ = "a cubed"
- $a^n$ = "a to the nth power"

**Roots**: $\sqrt{a}$ or $\sqrt[3]{a}$
- $\sqrt{a}$ = square root of a
- $\sqrt[3]{a}$ = cube root of a
- $\sqrt[n]{a}$ = nth root of a

### Basic Variables and Constants
**Variables**: Letters representing unknown values
- Most common: $x$, $y$, $z$ for unknowns
- Parameters: $a$, $b$, $c$ for constants in equations
- Functions: $f$, $g$, $h$ for function names

**Common Constants**:
- $\pi \approx 3.14159...$ (pi)
- $e \approx 2.71828...$ (Euler's number)
- $i = \sqrt{-1}$ (imaginary unit)

### Equality and Inequality
**Equals**: $=$
- Example: $x = 5$, $2 + 3 = 5$

**Not equals**: $\neq$
- Example: $x \neq 0$

**Inequalities**:
- $<$ less than
- $>$ greater than
- $\leq$ less than or equal to
- $\geq$ greater than or equal to

### Functions
**Function notation**: $f(x)$
- Read as "f of x"
- Example: $f(x) = x + 1$, $g(y) = y^2$

## Field Signatures
Basic arithmetic appears in **every** mathematical field, but you can identify you're looking at "basic math" when you see:
- Simple variable names ($x$, $y$, $a$, $b$)
- Basic operations without specialized symbols
- Elementary fractions and exponents
- Step-by-step algebraic manipulation

## Notation Conflicts
**The multiplication problem**: 
- $3 \times 4$ (elementary) vs $3 \cdot 4$ (physics) vs $3 * 4$ (programming) vs $3(4)$ or $3a$ (advanced math)
- **Context clue**: Elementary texts use $\times$, programming uses $*$, advanced math uses implicit multiplication

**The division problem**:
- $8 \div 2$ (elementary) vs $8/2$ (programming) vs $\frac{8}{2}$ (advanced math)
- **Context clue**: Elementary texts use $\div$, programming uses $/$, advanced math uses fraction notation
- **Why this matters**: If you see $\frac{2x + 1}{x - 3}$, you know you're looking at advanced math, not elementary arithmetic. The notation choice signals the mathematical sophistication level and helps you prepare for the type of reasoning expected.

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

## Why This Matters
Every advanced mathematical field assumes you're fluent in this basic notation. If you're not comfortable with these fundamentals, you'll get lost in the notation before you can even engage with the concepts. Master these, and you have the foundation for everything else.

## Next Steps
Once you're comfortable with these basics, you'll be ready to see how different fields build specialized notation on top of these fundamentals. Each field takes these core concepts and adds its own "dialect" of symbols and conventions.