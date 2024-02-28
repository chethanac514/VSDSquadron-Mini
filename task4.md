Meeting Held on: 27/02/2024

The C code should undergo the simulation of normal GCC X86 Compiler and riscv compiler (SPIKE Simulation)

AS PER THE REQUIREMENT OUTPUT OF GCC (F1) SHOULD BE EQUAL = TO OUTPUT OF RISCV GCC (F2)
![WhatsApp Image 2024-02-28 at 7 31 55 PM](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/1d5a80bc-823f-4c1d-b0c0-d1be7be3441b)
Step - 1: To Run the code in the normal GCC Compiler To compile the code: gcc sum1ton.c -o sum1ton To Get the output use "./a.out" : Here the output finds to be -Sum of numbers from 1 to 50 is 125250

Step - 2: To Run the code in the RISC-V GCC Compiler

To compile the code: riscv64-unknown-elf-gcc -o sum1ton sum1ton.c To Get the output use "./a.out" : Here the output finds to be -Sum of numbers from 1 to 50 is 125250

![Screenshot from 2024-02-28 22-13-00](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/a7e0c3cd-02da-4be9-9dcd-a0594309cbcb)

![Screenshot from 2024-02-28 22-18-36](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/e9248aa7-a8bc-4da1-b729-0e7368642112)

![Screenshot from 2024-02-28 22-22-57](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/c6d46728-ebeb-4ded-927d-1bcc46de2a0f)
