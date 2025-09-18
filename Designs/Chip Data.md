# Main Chips
### ALU =
Arithmatic and Logical Unit works on 4-Bit data from RA (register) and RB (register).

ALL Functions in ALU use "RA" as Register 1 and "RB" as Register 2.

For Single input functions, "RA" is considered.

#### Functions Include = 
- Adder(ADD)
- Subtractor (SUB)
- AND Gate for 4-Bit
- OR Gate for 4-Bit
- NOT Gate for 4-Bit
- XOR Gate for 4-Bit
- 2'Complement for 4-Bit

The Output is Stored to "RO" (register) and Carry to "RC" (register) and Borrow to "RW" by default.

It has **3 Inputs - RA , RB , Instruction** and **3 Outputs - RO , RC , RW**

---

### Control Unit = 
Control unit realys the "Instructions" , "To" , "From/Value" and manages Read and Write Flags in Register Memory.

#### Functions Include = 
- Relaying the Input Command
- COntrolling the Flags
 
It has **3 Inputs - Instruction , To, From/Value** and **5 Outputs - Instruction , To , From/Value , WF , RF**

---

### Register Memory =
There are 16 Registers defined **14 Registers have 4-Bit Size and 2 Registers have 1-Bit Size**

Registers R0 , R1 , R2 , R3 , R4 , R5 , R6 , R7 are general purpose registers.

Registers RA , RB are the only registers that supply values to the ALU.

Registers RO , RC , RW are Output registers for ALU and **can not be directly edited via "MOV" operator**.

Register RP is the only Register (along RC , RW) whose data is shown out without the use of any special operation.

Registers WF , RF work as Write and Read Flags respectively to enforce memory protection.

It has **8 Inputs - RO , RC , RW , Input Value (IN) , Input Address , Output Address , WF , RF** and **6 Outputs - RA , RB , RP , RC , RW , Output Value**

---

### Memory Allocation Unit = 
It performs the Main memory management function "MOV" and "STO". Permiting memory manipulation.

#### Functions Include = 
- STO operation allowing values to be stored to respective Register.
- MOV operation allowing values to be moved in between Registers.

It has **4 Inputs - Instruction , To , Value/From , Output value** and has **3 Outputs - Input Value(IN) , Input Address , Output Address**

---

All Chips work together in union to do the desired task to be performed by th CPU.

**The Coder is chip is only present to make sure that all the values are feed together so that any runtime errors are not caused**