# Values, Types and operators

- To be able to work with hugh quantities of bits without getting lost
  we must separate them into chuncks that represent pieces of information.
- In JavaScript environment those chuncks are called **_values_**.
- Though all values are made of bits, they play different roles, every value has a ****type****.

## Simple value types:

### Numbers

- JavaScript uses a fixed number of bits, 64 of them to store a single number value.
- The number of bits used (64) makes it limited to present numbers as 2<sup>64</sup>. which is 18 and 18 zeros after it.
- Those bits are also used to store negative numbers so one bit indicates the sign of the number.
- Some of these bits are used to present the decimal points.
- Since not all bits are used to represent numbers because some of them are used to present the sign and the decimal point then only 9 quadrillion is used (15 zeros) which is still pleasantly huge.
