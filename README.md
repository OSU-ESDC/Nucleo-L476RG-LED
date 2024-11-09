This repository contains some code that can run on a NUCLEO-L476RG board, and turns on an LED. 

To run this program on the NUCLEO-L476RG board:

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

###### In the client
