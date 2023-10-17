#making my first OS x86

the computer search for the boot sector, which is a 512 bytes long that ends a binary file that end with 55 aa<br>
so this is the startup hehe

to build the binaries and boot my os i run this commands:

nasm -f bin boot.asm -o boot.bin 

qemu-system-x86_64 boot.bin  
