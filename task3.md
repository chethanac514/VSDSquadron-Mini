By Referring to C-based Lab videos and RISC-V-based lab videos

Snapshots of the compiled C code and RISC-V

Step 1: check whether the leafpad is installed in ur machine by using the commands leafpad sum1ton.c& (sum1ton.c is the file name) If the leafpad editor is opened without any errors then type the C code. **If the leafpad is not installed in ur machine then install by using the following command

sudo snap install leafpad**

![ch1](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/5fbb0817-a4ec-4990-81d4-d6d3bf625d21)
**Step 2: Writing the C code in the leafpad editor using the following command

leafpad sum1ton.c&

![ch2](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/a26ec7c9-8f3c-4b5b-af00-c659b7c76fa6)
Step 3: After writing the C code save the editor by Ctrl+s

Step 4: Check for the errors by using the following command(compilation step)

gcc sum1ton.c

![ch3](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/40a84949-b4a9-423c-97cf-809e9602d543)
Step 5: Check the output by using the command

./a.out
![ch4](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/9303a4ef-7b57-4046-8737-af55b1530dd7)
The results will be displayed as

Sum of numbers from 1 to 500 is 125250

***RISCV Compilation and Execution

Step 1: View the C Code in the editor window using the following command

cat sum1ton.c
Step 2: Compile the code in riscv using the following command

riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c


![ch5](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/6d235b0f-b358-403c-836d-0420430d282d)
Step 2: Compile the code in riscv using the following command

riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c
![ch6](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/8e333e36-9365-4afc-bdb0-cf335f32c95c)

Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution


![ch7](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/e9c42bfc-1966-424f-b866-5ee4c7de8f40)

![ch8](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/754efdcf-a436-4c0d-a110-e6e2eec24295)
Step 4:

riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c
![ch9](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/97f61618-4cd5-49df-9b72-611fc5c51212)

![ch10](https://github.com/chethanac514/VSDSquadron-Mini/assets/160845855/f0fc0b58-0dcb-4aee-b46d-3c95af5f57a7)
