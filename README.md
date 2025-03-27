# Vector_Space

A vector space (also called a linear space) is a fundamental mathematical structure in linear algebra. It consists of a set of objects called vectors, along with two operations:

Vector Addition: You can add two vectors together, and the result is also a vector in the same space.

Scalar Multiplication: You can multiply a vector by a scalar (a number), and the result is still a vector in the same space.

Formal Definition of a Vector Space
A vector space 𝑉over a field F (such as real numbers R or complex numbers C) is a set of elements (vectors) that satisfy the following axioms:

1. Closure Properties
Closure under addition: If 
𝑢,𝑣∈𝑉u,v∈V, then 𝑢 + 𝑣∈𝑉u + v∈V.

Closure under scalar multiplication: If 
𝑣∈𝑉v∈V and 𝑐∈𝐹c∈F, then 𝑐⋅𝑣∈𝑉c⋅v∈V.

3. Addition Properties
Commutativity: 
𝑢+𝑣=𝑣 + 𝑢u+v=v+u

Associativity: 
(𝑢+𝑣)+𝑤=𝑢+(𝑣+𝑤)

Existence of a zero vector: There is a vector 
0∈𝑉0∈V such that 𝑣+0=𝑣v+0=v for all 𝑣∈𝑉v∈V.

Existence of additive inverses: For every 
𝑣∈𝑉v∈V, there exists −𝑣−v such that 𝑣+(−𝑣)=0.

3. Scalar Multiplication Properties
Distributivity over vector addition: 
𝑐(𝑢+𝑣)=𝑐𝑢+𝑐𝑣

Distributivity over scalar addition: 
(𝑎+𝑏)𝑣=𝑎𝑣+𝑏𝑣 

Associativity: 
𝑎(𝑏𝑣)=(𝑎𝑏)𝑣

Multiplicative identity: 
1𝑣=𝑣1v=v, where 11 is the multiplicative identity in 𝐹.

source: https://www.freecodecamp.org/learn/scientific-computing-with-python/#learn-special-methods-by-building-a-vector-space
