# segfault_explain
Translates linux segfault error numbers to english using bitwise ops. 
From http://lxr.free-electrons.com/source/arch/x86/mm/fault.c
 26 /*
 27  * Page fault error code bits:
 28  *
 29  *   bit 0 ==    0: no page found       1: protection fault
 30  *   bit 1 ==    0: read access         1: write access
 31  *   bit 2 ==    0: kernel-mode access  1: user-mode access
 32  *   bit 3 ==                           1: use of reserved bit detected
 33  *   bit 4 ==                           1: fault was an instruction fetch
 34  */
