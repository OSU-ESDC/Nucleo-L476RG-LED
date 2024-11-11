## This repository contains some code that can run on a Nucleo-L476RG board, and turns on an LED. 

The following describes the entire build process:

### For Linux users:
#### Clone the repository 
```
git clone git@github.com:OSU-Embedded-Systems-Design-Club/Nucleo-L476RG-LED.git
cd Nucleo-L476RG-LED/src
make
```

###### Open two terminals: one for client and one for server
For server:
```
make load
```

For client:  
###### To open a folder from WSL in VScode, just cd into that folder and use the command:
```
code .
```
  

```
make client
```
```
(gdb) start
```
-> should now see the green LED on the Nucleo-L476RG board light up!  

