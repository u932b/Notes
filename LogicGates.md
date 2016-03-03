[Slide Link](http://www.csd.uwo.ca/~lila/logic/logicgates.pdf)

## Bit
* [b]inary dig[it]
* John Turkey, 1946

## Boolean variable
* If its value is either true or false
* Let B = {0, 1}. x is Boolean variable if x $\in$ B

## Boolean Functions
B is called a Boolean function of degree n

$$B^n = \{(x_1, x_2, x_3, ...)|x_i\in B,\ 1\leq i \leq n\}$$

* Often displayed as truth tables, e.g $F(x,y) = x + y$

x|y|$F(x,y)$
-|-|-------
1|1|1
1|0|1
0|1|1
0|0|0
* The number of Boolean functions of degree n

Degree|Number
------|------
1|$2^2$
2|$(2^2)^2$
3|$((2^2)^2)^2$
.|...


## Bit Operations -> Bitwise Operations
### Bit Operations
* OR
* AND
* XOR

### Bitwise Operations
* Bitwise OR
* Bitwise AND
* Bitwise XOR

#### Bit String
Just means a sequence of zero or more bits

## Boolean Operations
* George Boole (1815 - 1864)
* propositional calculus can be translated into Boolean Algebras*
* One Unary Operation
    * Complement ($\overline{x_i}$)
* Two Binary Operations
    * Boolean Sum (OR, +)
    * Boolean Product (AND, $\cdot$)
* Every Boolean function can be expressed using $\{+, \cdot, \overline{x}\}$, this set of operators is **functionally complete**
* Functionally complete set
    * $\{+,\overline{x}\}$
    * $\{\cdot, \overline{x}\}$
    * $\{\uparrow\}$ NAND operator or Sheffer Stroke
    * $\{\downarrow\}$ NOR operator


## Boolean Algebra
* Identity laws: $x+0=x,\ x\cdot 1=x$
* Domination laws: $x+\overline{x}=1,\ x\cdot \overline{x}=0$
* Associative laws (結合律): $(x+y)+z=x+(y+z),\ (x\cdot y)\cdot z =x\cdot (y\cdot z)$
* Commutative laws (交換律): $x+y=y+x,\ x\cdot y=y\cdot x$
* **Distributive laws (分配律): $x+(y\cdot z)= (x+y)\cdot (x+z),\  x\cdot(y+z)=(x\cdot y)+(x\cdot z)$**
    1. $x+xy =x$
    2. $x+\overline{x}y=x+y$

## Half-Adder

##Adder
