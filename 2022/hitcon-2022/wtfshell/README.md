The bug is in strtok and remove\_slash, allowing us a null byte overwrite to 0x21 '!'. Another bug is non-null terminated password, which gives us heap leak. Heap massage and use bug to backwards consolidate overlapping chunks. Tcache dupe onto stack, ropchain into shellcode, use openat in 32-bit mode to bypass seccomp.