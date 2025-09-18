
# EXPERIMENT 01 ALP FOR 8086
### Name : R.Rubasri
### Roll no : 212224240139




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

## Addition  of 16 bit ALP 
```
org 100h

mov ax,3274h
mov bx,5324h
add ax,bx
ret
```

## Output 
<img width="1354" height="691" alt="image" src="https://github.com/user-attachments/assets/319697cc-578e-421f-bc17-f7a812247da0" />

 
## Subtraction   of 16 bit numbers  ALP 
```
org 100h

mov ax,3274h
mov bx,[3274h]
sub ax,bx
ret
```
 
## Output  
<img width="1362" height="712" alt="Screenshot 2025-08-18 143105" src="https://github.com/user-attachments/assets/4ed59f7a-77cb-4c62-a55d-cb9d241e0345" />


## Multiplication alp 
```
org 100h  
mov ax,0778h
mov bx,0756h
mul bx
ret
```

 ## Output  
<img width="1264" height="633" alt="image" src="https://github.com/user-attachments/assets/7713fb2f-3dcc-4ee4-b9c7-37aff82364b6" />



## Division alp 
```
org 100h  
mov ax,2345h
mov bx,[5432h]
div bx
ret
```
## Output  
<img width="1363" height="716" alt="image" src="https://github.com/user-attachments/assets/301c89a9-9e63-444b-af6c-64f032cde1fc" />

## AND of 16 bit numbers ALP
```
org 100h
mov ax,643ch
mov bx,7456h
and ax,bx
ret
```
## Output

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1155484e-b89f-4b14-9754-6d86795bbdd2" />


## Or of 16 bit numbers ALP
```
org 100h
mov bx,7cadh
or ax,[bx]
ret
```
## output
<img width="1253" height="642" alt="image" src="https://github.com/user-attachments/assets/dde966b3-d99b-4e0f-b5e5-01a98677b193" />


## NOT of 16 bit numbers ALP
```
org 100h
mov ax,[7abch]
not ax
ret
```
## output
<img width="1280" height="613" alt="image" src="https://github.com/user-attachments/assets/0c2cbe39-02b3-4f5b-8380-5e94077602e2" />


## XOR of 16 bit numbers ALP
```
org 100h
mov ax,[78ach]
mov bx,576ah
xor ax,bx
ret
```
## Output:
<img width="1280" height="642" alt="image" src="https://github.com/user-attachments/assets/9d55454c-cdeb-4265-8575-cc44813c30a6" />



## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








