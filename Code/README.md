# v0100

In this varient methods and loop are not added.

There are 14 defined Operators and 16 Registers.

Details about them could be found in remaing files in the directory.

---

---

# Code Structure
<pre>
[v0100] //Version Declaration

start:
    <\operator> <\to Register>, <\from Register / Value>
    STO RA, 4
    STO RB, 5
    ADD
    MOV RP, RO
</pre>

Comments are not implemented in the compiler version V1.0.0 .

Max value that could be stored is 15 (1111).

---

---

# Interpreter

It is named Lily.

It could be found in my Other Github repo.

Link = 

---

Code should be stored with ".lil" extension and will be compiled to ".rsh".

".rsh" file stores binary values which you can directly input in the CPU.

More details can be found in that repostiery.

---