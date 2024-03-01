**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& ![WhatsApp Image 2024-03-01 at 17 49 01_e4eedef5](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/a0362940-9c27-48f4-b0c5-6fa7064855c7)

If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****


****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![WhatsApp Image 2024-03-01 at 17 49 09_69246e9a](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/99a85754-580d-44f4-8a85-c4ca5c976a1f)

**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**
![WhatsApp Image 2024-03-01 at 17 49 10_2e89c221](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/71dcbb92-4f10-4b64-97a8-52c1e51d64f8)

**Step 5: Check the output by using the command**

**./a.out**
![WhatsApp Image 2024-03-01 at 17 49 10_2e89c221](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/b4e1facd-4348-4a02-8cfd-32e474169d34)

**The results will be displayed as** 

**Sum of numbers from 1 to 67 is 2278**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![WhatsApp Image 2024-03-01 at 17 49 10_fc34577a](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/9d13d7c9-8e6b-4072-a129-fd6984c39c11)

**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
![WhatsApp Image 2024-03-01 at 17 49 11_27dd0332](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/084314c0-249f-4d73-a60c-5cf8ec607e97)

**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**
![WhatsApp Image 2024-03-01 at 17 49 11_8081b534](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/64eb88a7-5835-46a0-8c96-25ffad44cf8b)




**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![checking instructions_in_main_C_Code_15_instructions]![WhatsApp Image 2024-03-01 at 17 49 12_226e0e3b](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/88fdfc5c-3ae9-46cd-890b-dc3d5a64fcc2)


![checking instructions_in_main_C_Code_15_instructions_highlighted](https://github.com/Abdulbitm/Abdul/assets/160620896/0a07ba3e-4a3d-41a7-a158-3ef976ce0292)


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
![WhatsApp Image 2024-03-01 at 17 49 12_55fd3658](https://github.com/Ekanthreddy886/ekanth-reddy/assets/159982724/65fd5e0d-1244-40a8-b5da-372818d06ef6)









