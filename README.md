# KISS bootloader

**KISS bootloader** is a really simple bootloader of only 680bytes that can boot up any compliant boot sector from any support.

It discovers all devices and pass them along with the corresponding media ID to the boot sector after loading it at address 0.

Please do not hesitate to contribute to this bootloader ~~(The code is documented)~~.

For more documentation, see the top of *bootloader.dasm*. *bootsector.dasm* contains an example bootsector.

Compiles with [Yamakaky's assembler] (https://github.com/Yamakaky/dcpu)
