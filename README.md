# bootanim.xex
This is an a bootanim.xex C++ recreation (Work in progress).

I have found the correct compiler and projects setting as well as the entry point for the bootanim.xex call on system startup.
The next step is to initalize DirectX but for some reason the xex crashes while doing this on start up which is going to require some more reverse engineering of the original xex.

Must be compiled as a Dynamic Library!

Must use the Base address of: 0x98000000 (In IDA this will be shown as 0x98000400)

Must use 4-KB memory page size to use this base address!!
