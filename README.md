This project explores the low-level boot process of x86 systems.
It starts with writing a 16-bit Master Boot Record (MBR) that boots directly via BIOS, then advances to loading a 32-bit protected-mode kernel using GRUB and the Multiboot specification.

The project demonstrates how a computer transitions from firmware to bootloader to kernel — without relying on any operating system abstractions.
