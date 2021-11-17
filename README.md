# zynq7015_linux_base

#### zynq armv7 embeded linux fs whit PS ETH and serial port 
#### Build version
##### --Ubuntu 16.04
##### --Petalinux 2017.4
##### --Vivado 2017.4

### running Step
##### 1 copy the image.ub and BOOT.bin to sd/tf card (format the card to fat32 if not)
##### 2 config the board start from sd card
##### 3 connect to serial cable and plug the card to board, Then power on！
##### 4 open the serial terminal in the pc , watch the output


##### 5 using the root (user name) to login, pwd root(same with user name)
##### 6 connect the ETH cable with the PS PHY port, you should watch the macb .... link up(1000/Full) print in the terminal
##### 7 In the terminal using ifconfig to show the eth port status
