# boot-loader
Boot loader built using assembly. 
</br>
Learning assembly, and how bootloaders work. 
</br>
Used WSL-Ubuntu. 
</br>
## Installation
<br/>
Nasm
<br/>
<code>sudo pacman -S nasm</code>
<br/>
</br>
Install Qemu emulator
<br/>
<code>sudo apt-get install qemu</code>
<br />
<br/>
Create the binary when done with the code
<br/>
<code>nasm -f bin boot.asm -o boot.com</code>
</br>
</br>
Run Qemu 
<br/>
<code>qemu-system-i386 -fda boot.com</code>
