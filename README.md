# CIS310---GROUP-assignment-1
Design Choices

General_Purpose_Register- Input (provides 4-bit values to address pointed to), Address (2-bit and it controls what register is being modified or loaded), output (shows current register value that address is pointing to), CTRL (read and write function, read is 0, write is 1, clear is 2).

4-bit-register- X (input of 4 bits), Y (output of 4-bits), CTRL (Read, write, and clear. 0 is read, 1 is write, 2 is clear)

Program-counter- 4 bit adder (increments the value by one constantly) CTRL(read, write, clear, 0,1,2).

Instruction-Register- Input (input of 4 bits), Output (output of 4-bits), CTRL (Read, write, and clear. 0 is read, 1 is write, 2 is clear)

Registers_DRAM - Program counter (gives input to Address), Address (provides address to Dram), Input_Mem (gives input to IR), IR (shows output of current address), All CTRL (Load, set, reset)

Test SS

4 bit Register:
![image](https://github.com/user-attachments/assets/fbe0adbc-b946-4cd6-9602-93278bc69a81)

DRAM:
![image](https://github.com/user-attachments/assets/5d408d54-814f-4d3f-bd68-da5c6b8610d1)

Program Counter :
![image](https://github.com/user-attachments/assets/dee95c76-a23f-4bfd-af77-01bd1fc98833)
![image](https://github.com/user-attachments/assets/cde4174e-b33b-4a02-a37d-cc0dc29c504b)

Instruction Register:
![image](https://github.com/user-attachments/assets/64d7e070-37da-406b-8041-6d31580cb002)

Complete Circuit:
![image](https://github.com/user-attachments/assets/fe52cfc5-f9a2-4550-8ac0-155133f06bd2)






