# Introduction to Buffer Overflows

**Steps**

1. Crash The Application
2. Find EIP
3. Control ESP
4. Identify Bad Characters
5. Find JMP ESP
6. Generate Shell Code
7. Exploit

**Definitions**

1. EIP - The Extended Instruction Pointer \(EIP\) is a register that contains the address of the next instruction for the program or command.
2. ESP – The Extended Stack Pointer \(ESP\) is a register that lets you know where on the stack you are and allows you to push data in and out of the application.
3. JMP – The Jump \(JMP\) is an instruction that modifies the flow of execution where the operand you designate will contain the address being jumped to.
4. \x41, \x42, \x43 - The hexadecimal values for A, B and C. For this exercise, there is no benefit to using hex vs ascii, it's just my personal preference.

**Really good introduction to buffer overflows**

{% embed url="https://github.com/gh0x0st/Buffer\_Overflow" %}

Excellent playlist from [The Cyber Mentor](https://www.youtube.com/c/TheCyberMentor) \(TCM\) 

{% embed url="https://www.youtube.com/playlist?list=PLLKT\_\_MCUeix3O0DPbmuaRuR\_4Hxo4m3G" %}



### 

