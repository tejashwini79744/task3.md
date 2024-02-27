By Referring to C-based Lab videos and RISC-V-based lab videos

Snapshots of the compiled C code and RISC-V

Step 1: check whether the leafpad is installed in ur machine by using the commands leafpad sum1ton.c& (sum1ton.c is the file name) If the leafpad editor is opened without any errors then type the C code. **If the leafpad is not installed in ur machine then install by using the following command

sudo snap install leafpad**
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/dc7ed285-2557-4df2-8d97-d8d70dbc0a66)

**Step 2: Writing the C code in the leafpad editor using the following command

leafpad sum1ton.c&
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/c29c288a-9b53-4840-8b15-19b0b0906a68)

Step 3: After writing the C code save the editor by Ctrl+s

Step 4: Check for the errors by using the following command(compilation step)

gcc sum1ton.c
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/8ad91a94-dac3-4eff-b983-65877d014ebf)

Step 5: Check the output by using the command

./a.out
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/d342660a-8d2d-4b55-879d-ea5245071510)

The results will be displayed as

Sum of numbers from 1 to 500 is 125250
***RISCV Compilation and Execution
Step 1: View the C Code in the editor window using the following command
cat sum1ton.c
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/38354ee7-7b92-4d32-b78c-9d3c75df8c6a)

Step 2: Compile the code in riscv using the following command

riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c


![image](https://github.com/tejashwini79744/task3.md/assets/161418020/7b516e73-7ee0-4ad0-a12a-46253f511af7)

Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.
use the command Is-Itr sum1ton.c
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/44d2aa39-db86-4af6-acc8-071f83c5e2dd)
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/66b9a0f4-45b9-4548-837d-2cc3d70fedc0)
Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution 
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/1acc4ddb-d7e0-4215-97a1-7c3a0f4868f1)
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/3fb1a735-9cb4-493e-8107-28fdd80e5b95)
Step 4:

riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c
![image](https://github.com/tejashwini79744/task3.md/assets/161418020/353d0801-6ab7-47b2-829c-abaafd9281ed)

![image](https://github.com/tejashwini79744/task3.md/assets/161418020/dabd5719-3dac-4176-b5b2-9064ff32168c)

















