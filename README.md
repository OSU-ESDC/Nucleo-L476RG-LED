This repository contains some code that can run on a Nucleo-L476RG board, and turns on an LED. 

Build Process from start to flashing the mcu:

### For Linux users:
#### Clone the repository 
```
git clone username@github.com:OSU-Embedded-Systems-Design-Club/Nucleo-L476RG-LED.git
cd Nucleo-L476RG-LED
cd src
make
```

###### Open two terminals: one for client and one for server
For server:
```
make load
```

For client:
```
make client
```
```
(gdb) start
```
-> should now see the green LED on the Nucleo-L476RG board light up!  
