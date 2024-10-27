# Values, Types and operators

- To be able to work with hugh quantities of bits without getting lost
  we must separate them into chuncks that represent pieces of information.
- In JavaScript environment those chuncks are called **_values_**.
- Though all values are made of bits, they play different roles, every value has a \***\*type\*\***.

## Simple value types:

### NUMBERS

- JavaScript uses a fixed number of bits, 64 of them to store a single number value.
- The number of bits used (64) makes it limited to present numbers as 2<sup>64</sup>. which is 18 and 18 zeros after it.
- Those bits are also used to store negative numbers so one bit indicates the sign of the number.
- Some of these bits are used to present the decimal points.
- Since not all bits are used to represent numbers because some of them are used to present the sign and the decimal point then only 9 quadrillion is used (15 zeros) which is still pleasantly huge.
- for very big or very small numbers you may use scientific notation by adding an `e` (for exponent) -> 2.9998e8 = 2.998 x 10 <sup> 8 </sup> = 299,800,00.

- Calculations on integers smaller than the 9 quadrillion are guaranteed to be precise.
- Calculations on fractional numbers can't be precisely expressed by a finite number.

> [!IMPORTANT]
> Treat fractional numbers always as approximations not as a precise values.

### ARTHIMATIC OPERATIONS

- Arithmetic progression is followed in JavaScript 100 + 4 \* 11 means that the multiplication happens first.
- But as in mathematics you can change this by wrapping in parentheses (100 + 4 )\* 11.
- When operators appear together without parentheses, the order in which they are applied is determined by the precedence of the operators.
- The / operator has the same precedence as \*, Likewise + and -.

The arithmetic precedence in JavaScript is the same as in mathematics;
The order is

1. **Parentheses ()**
2. **Exponents \*\***
3. **Multiplication \*, Division /, and Remainder %**
4. **Addition + and Subtraction -**

```
let result = 3 + 4 * 2 // is 11 not 14
```

```
let result = (3 + 4) * 2 // is 14 not 11
```
