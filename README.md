# boot-loader
Boot loader built using assembly. 
</br>
Learning assembly, and how bootloaders work. 
</br>
Used WSL-Ubuntu. 
</br>
## Installation
<br/>
#### nasm
<code>sudo pacman -S nasm</code>
#### Install Qemu emulator
<code>sudo apt-get install qemu</code>
### Create the binary when done with the code
<code>nasm -f bin boot.asm -o boot.com</code>
#### Run Qemu 
<code>qemu-system-i386 -fda boot.com</code>
