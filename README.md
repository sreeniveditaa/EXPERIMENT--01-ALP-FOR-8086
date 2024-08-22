# EXPERIMENT--01-ALP-FOR-8086
Name : Sree Niveditaa saravanan
Roll no : 212223230213 
Date of experiment :





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h
MOV al,11h;
MOV bl,20h;
ADD al,bl;
MOV [4000h],al;
ret
```

## Output  

![addition](https://github.com/user-attachments/assets/afa6a3c4-c54c-4c1b-bd91-f0603e0f87ea)

## Subtraction   of 8 bit numbers  ALP 
```
org 100h
MOV al,20h;
MOV bl,[2000h];
SUB bl,al;
MOV [3000h],bl;
ret
```

## Output 

![subraction](https://github.com/user-attachments/assets/45327ba0-3cb2-41d3-94c2-cc653a3bbe57)

## Multiplication alp
```
org 100h
MOV al,13h;
MOV bl,2h;
MUL bl;
MOV [6000h],al;
ret
```

 ## Output  

![multiplication](https://github.com/user-attachments/assets/6912b517-eaba-4e00-a140-e589ebd3b1db)

## Division alp 

```
org 100h
MOV al,26h;
MOV bl,[2000h];
DIV bl;
MOV [3000h],al;
ret
```

## Output  

![division](https://github.com/user-attachments/assets/b8ab5d2b-5018-477d-9051-918b5002761c)

## AND alp

```
org 100h
MOV [SI],AX;
MOV AX,0A32H;
MOV BX,0B13H;
AND AX,BX;
ret
```

## Output :

![and](https://github.com/user-attachments/assets/b4fca661-4c3f-4702-8ded-ab7971e1b279)

## OR alp

```
org 100h
MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
ret
```

## Output :

![or](https://github.com/user-attachments/assets/f450c12b-0d00-4251-99f6-e3cdb708cde9)

## NOT alp

```
org 100h
MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
ret
```

## Output :

![not](https://github.com/user-attachments/assets/00d1b3d7-e2bc-4d72-b3fc-566d7d356413)

## XOR alp

```
org 100h
MOV [SI+2],AX;
MOV AX,0A32H;
MOV BX,0B13H;
XOR AX,BX;
ret
```

## Output :

![xor](https://github.com/user-attachments/assets/6730e32f-a294-4c09-91a4-e8f233827589)


## Result :
Thus, Assembly Language Program for fundamental arithmetic and logical operations are exected succesfully. 








