# Identify instruction types and exact 32-bit instruction code in the instruction type format
<b>RISC-V instructions are encoded using a fixed-length 32-bit format, which simplifies decoding and execution. The instruction formats are categorized into six types: R, I, S, B, U, and J. Each format serves a specific purpose and has a unique encoding structure:

<b></p>R-type instructions:
>Used for register-to-register operations, such as arithmetic and logical operations.</br>
>They include three register operands: two source registers and one destination register.</br>
> Eg:- add (Add 2 registers and store results in another)</br>

<b></p>I-type instructions:
>Used for immediate operations, such as arithmetic and logical operations with an immediate value.</br>
> They include two register operands and a 12-bit immediate value.</br>
>Eg:- li (Load immediate value)</br>

<b></p>S-type instructions:
>Used for store operations, which store data from a register to memory.</br>
>They include two register operands and a 12-bit immediate value for the memory address offset.</br>
> Eg:- sw (store the value in register)</br>

<b></p>B-type instructions:
>Used for conditional branch operations, which transfer control to a different instruction based on a condition.</br>
>They include two register operands and a 12-bit immediate value for the branch target address.</br>
> Eg:- beq (compare and label)</br>

<b></p>U-type instructions:
>Used for operations with a 20-bit immediate value, such as loading a 20-bit constant into a register or setting the upper 20 bits of a register.</br>
>Eg:- lui (load upper immediate value)</br>

<b></p>J-type instructions:
>Used for unconditional jump operations, which transfer control to a different instruction unconditionally.</br>
>They include one register operand and a 20-bit immediate value for the jump target address.</br>
> Eg:- J (jump)</br>
