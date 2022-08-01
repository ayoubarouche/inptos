# inptos
operating systems using C++

# We will use grub as bootloader for our operating system (we will create a costum bootloader later)

# to use grub you must install the current package else it will not work : 

sudo apt-get install grub-pc-bin

# to generate an iso file please use the command 

make mykernel.iso

# to run using qemu use this command : 

make run 

