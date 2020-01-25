# NOS

Nostromo OS

Nostromo OS or NOS for short, is a real-time operating system inpired by the Sevastolink personal terminal in Alien: Isolation and variations of the Nostromo terminal in the Alien franchise.

NOS is inteded to be a fully functional operating system, with its own kernel, ABI, file system, comunication protocols, device drivers, and more, while still being Linux compatible. NOS will be developed from scratch, drawing inspiration from MS-DOS, UNIX, Linux, and others. Building an operating system is a massive undertaking, and the help of both kristina-n and mjkurpiewski is greatly appreciated.

TODO :

- We need to start thinking about what OS structure would most benefit the project. Since NOS will mostly support ARM based systems, we can't go wrong with a microkernel design; implementing file systems and other non-essentials as usel level programs.
- We need to research booting sequences on freestanding systems, BIOS, and UEFI. I've read quite a bit on BIOS, but not the other two.
- ...
