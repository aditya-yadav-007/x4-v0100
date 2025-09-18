|Binary|Name|Description|Use|
|------|----|-----------|---|
|0000|SUS| Start up State|Default|
|0001|  |   |   |
|0010|MOV|Moves data from Register 1 to Register 2| MOV < to > < from >|
|0011|STO|Stores Data to a Resgister| STO < to > < value >|
|0100|WFC| Write Flag Closed = No Data can be written| WFC|
|0101|WFO| Write Flag Open = Data can be written| WFO
|0110|RFC| Read Flag Closed = No Data can be read|RFC|
|0111|RFO|Read Flag Open =  Data can be read| RFO|
|1000|ADD|Adder is Used in ALU| ADD < RA > < RB > (Registers are Fixed)|
|1001|SUB|Subtractor is used in ALU|SUB< RA > < RB > (Registers are Fixed)|
|1010|AND|AND Logic is used in ALU| AND < RA > < RB > (Registers are Fixed)|
|1011|OR| OR Logic is used in ALU| OR < RA > < RB > (Registers are Fixed)|
|1100|NOT|NOT Logic is used in ALU| NOT < RB > (Registers are Fixed)|
|1101|XOR|XOR Logic is used in ALU| XOR < RA > < RB > (Registers are Fixed)|
|1110|COM|2's Complement| COM < RA > (Registers are Fixed)|
|1111|  |   |  |
---
