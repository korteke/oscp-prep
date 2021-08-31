# Introduction to Buffer Overflows

## Background

Buffers are memory storage regions that temporarily hold data while it is being transferred from one location to another. A buffer overflow \(or buffer overrun\) occurs when the volume of data exceeds the storage capacity of the memory buffer. As a result, the program attempting to write the data to the buffer overwrites adjacent memory locations.

For example, a buffer for log-in credentials may be designed to expect username and password inputs of 8 bytes, so if a transaction involves an input of 10 bytes \(that is, 2 bytes more than expected\), the program may write the excess data past the buffer boundary.

Buffer overflows can affect all types of software. They typically result from malformed inputs or failure to allocate enough space for the buffer. If the transaction overwrites executable code, it can cause the program to behave unpredictably and generate incorrect results, memory access errors, or crashes.

## **Steps**

1. Crash The Application
2. Find EIP
3. Control ESP
4. Identify Bad Characters
5. Find JMP ESP
6. Generate Shell Code
7. Exploit

### **Definitions**

1. EIP - The Extended Instruction Pointer \(EIP\) is a register that contains the address of the next instruction for the program or command.
2. ESP – The Extended Stack Pointer \(ESP\) is a register that lets you know where on the stack you are and allows you to push data in and out of the application.
3. JMP – The Jump \(JMP\) is an instruction that modifies the flow of execution where the operand you designate will contain the address being jumped to.
4. \x41, \x42, \x43 - The hexadecimal values for A, B and C. For this exercise, there is no benefit to using hex vs ascii, it's just my personal preference.

**Really good introduction to buffer overflows**

{% embed url="https://github.com/gh0x0st/Buffer\_Overflow" %}

Excellent playlist from [The Cyber Mentor](https://www.youtube.com/c/TheCyberMentor) \(TCM\) 

{% embed url="https://www.youtube.com/playlist?list=PLLKT\_\_MCUeix3O0DPbmuaRuR\_4Hxo4m3G" %}



### 

