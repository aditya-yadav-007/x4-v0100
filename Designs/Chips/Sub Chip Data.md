# Sub Chips =

---

These chips are the smaller chips which are used in the Main chips.

### AND - 3 =

Its an AND gate.

Working on 3 Inputs and giving 1 output.

O = A . B . C 

---

### AND - 4 =

Its an AND gate.

Working on 4 Inputs and giving 1 output.

O = A . B . C . D

---

### AND 4X2 =

Its an AND gate.

Working on 2 Inputs of 4-Bits and 1 Input of 1-Bit acting as On switch and giving out 1 Output of 4-Bits.

O(4-Bits) = A(4-Bits) . B(4-Bits) . C(Signal)

---

### Not 4X1 =

Its a NOT gate.

Working on 1 Input of 4-Bits and 1 Input of 1-Bit acting as ON signal and giving an Output of 4-Bits.

O(4-Bits) = `A(4-Bits).B(signal)

---

### OR - 8 =

Its an OR Gate.

Working on 8 inputs and giving 1 output.

O  = A + B + C + D + E + F + G + H

---

### OR 4X2 =

Its an OR gate.

Working on 2 Inputs of 4-Bits and giving an Output of 4-Bits.

O(4-Bits) = A(4-Bits)+B(4-Bits)

---

### OR 4X8 =

Its an OR gate.

Working onr 8 Inputs of 4-Bits and giving an Output of 4-Bits.

O(4-Bits)  = A(4-Bits) + B(4-Bits) + C(4-Bits) + D(4-Bits) + E(4-Bits) + F(4-Bits) + G(4-Bits) + H(4-Bits)

---

### OR 4X2 - ALU =

Its an OR gate (used in ALU)

Working on 2 Inputs of 4-Bits and 1 input of 1-Bit (acting as ON Signal) and giving an Output of 4 Bits.

O(4-Bits) = [A(4-Bits) + B(4-Bits)] . C(ON Signal)

---

### XOR 4X2 =

Its an XOR Gate (ised in ALU)

Working on 2 Inputs of 4-Bits and 1 input of 1-Bit (acting as ON Signal) and giving an Output of 4 Bits.

O(4-Bits) = [A(4-Bits) (+) B(4-Bits)] . C(ON Signal)

---


### Buffer / Coder =

It is like a stop valve. Only allows 4 Bit data to pass when the Input Signal is on.

Works on 1 Input of 4-Bits and 1 Input of 1 Bit (Signal), giving 1 Output of 4-Bits.

O(4-Bits) = A(4-Bits) . B(Signal)
 
---

### Splitter =

It splits the input signal to 2 Signals of same kind.

Works on 1 Input of 4-Bits and 2 Outputs of 4-Bits.

---

### Adder =

Its a combination of gates used to add 2 bits together.

Works on 3 Inputs A , B and Carry Input and gives 2 Outputs O and Carry Out.

---

### Subbtractor =

Its a combination of gates used to subtrat 2 bits together.

Works on 3 Inputs A , B and Borrow Input and gives 2 Outputs O and Borrow Out.

---
### S R Latch = 

Or so called Set Reset Latch. Its a form of Volatile memory which stors data in form of 1 / 0 till the system is powered on.

It has 2 Inputs Set(1) and Reset(0) and has 2 output O and O'(Its the opposite of "O").

---

### Writer =

Its Combination of gates NAND , AND and NOT to write Value to S R Latch. It receives data and toggels on the respective input of S R Latch.

If the Value is 0 its sets the Reset (0) pin high and if the data is 1 it sets the Set(1) pin high.

It has 1 Input and 2 Output.

---



**Unless Specified**

GATES = AND, OR, NOT, XOR, NAND, NOR are assumed to be predefined.
