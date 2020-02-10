![NOS Logo](nos.png)

## Nostro OS

Nostro OS or NOS for short, is a real-time operating system inpired by the Sevastolink personal terminal in Alien: Isolation and variations of the Nostromo terminal in the Alien franchise.

NOS is intended to be a fully functional operating system with its own kernel, ABI, device drivers, file system, communication protocols, and more. The operating system will be developed from scratch, drawing inspiration from MS-DOS, UNIX, Linux, and others. Building an operating system is a massive undertaking and the help of the collaborators is greatly appreciated.

TODO :

- What OS design structure would most benefit the project? Since NOS will mostly support ARM based systems, one can't go wrong with a microkernel design; implementing file systems and other non-essentials as usel level programs.
- Currently researching booting sequences on freestanding systems, BIOS, and UEFI. I've read quite a bit on BIOS, but not the other two.
- Next on the list is identifying potential drawbacks in the design to keep the system up to modern standards
