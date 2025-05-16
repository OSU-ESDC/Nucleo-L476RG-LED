## This repository contains some code that can run on a Nucleo-L476RG board, and turns on an LED. 

The following describes the entire build process:

### Clone the repository 
```
git clone git@github.com:OSU-ESDC/Nucleo-L476RG-LED.git
cd Nucleo-L476RG-LED/src
make
```

###### Open two terminals: one for client and one for server
For server:
```
make load
```

###### To open a folder from WSL in VScode, just cd into that folder and use the command: `code .`

For client (either in other WSL terminal or in VSCode terminal):  

```
make client
```
```
(gdb) start
```
-> should now see the green LED on the Nucleo-L476RG board flash!  

