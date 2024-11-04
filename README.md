The following project contains the verilog code of a miniature 4-bit ALU(arithmetic logic unit).
A miniature 4-bit unsigned ALU which performs the following operations
depending upon a 4-bit op-code “OP” :
| OP  | Action |
| ------------- | ------------- |
| 0000  |  NOP |
| 0001  | Add two operands (operand1 + operand2)  |
| 0010  | Subtract two operands (operand1 – operand2)  |
| 0011  | Bit-wise AND the two operands  |
| 0100  | Bit-wise XOR the two operands |
| 0101  | Bit-wise OR the two operands  |
| 0110  | Generates the 2s-complement of the operand1 |
| 0111  | Bit-wise inverts the operand1  |
| 1000  | Shift operand1 left by operand2 bits.   |
| 1001  | Shift operand1 right by operand2 bits.   |
| 1010  | Rotate operand1 left by operand2 bits.   |
| 1011  | Rotate operand1 right by operand2 bits.   |
