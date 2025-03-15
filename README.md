# CIS310---GROUP-assignment-1
Design Choices

General_Purpose_Register- Input (provides 4-bit values to address pointed to), Address (2-bit and it controls what register is being modified or loaded), output (shows current register value that address is pointing to), CTRL (read and write function, read is 0, write is 1, clear is 2).

4-bit-register- X (input of 4 bits), Y (output of 4-bits), CTRL (Read, write, and clear. 0 is read, 1 is write, 2 is clear)

Program-counter- 4 bit adder (increments the value by one constantly) CTRL(read, write, clear, 0,1,2).

Intruction-counter- Input (input of 4 bits), Output (output of 4-bits), CTRL (Read, write, and clear. 0 is read, 1 is write, 2 is clear)

DRAM_with_registers - Program counter (gives input to Address), Address (provides address to GPR), Input_Mem (gives input to IR), IR (shows output of current address), All CTRL (Load, set, reset)

Test SS

4 bit Register:
![image](https://github.com/user-attachments/assets/fbe0adbc-b946-4cd6-9602-93278bc69a81)

General Purpose Register:
![image](https://github.com/user-attachments/assets/57efe566-a3a5-4735-8c03-c837937dd641)


Program Counter : (Wasn't sure how to show increment with a screenshot)
![image](https://github.com/user-attachments/assets/4ab04760-7ccd-4687-a219-48cfae873d79)
![image](https://github.com/user-attachments/assets/267702eb-381e-49f0-8cec-affa8f755464)

Instruction Register:
![image](https://github.com/user-attachments/assets/64d7e070-37da-406b-8041-6d31580cb002)

Complete Circuit:
![image](https://github.com/user-attachments/assets/4b4d4ed7-8099-4095-99d5-2e64c0039d47)





