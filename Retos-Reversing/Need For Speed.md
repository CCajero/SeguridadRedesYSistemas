## Objetivo

## Solución

	ccajero-picoctf@webshell:~/NeedForSpeed$ gdb need-for-speed
	(gdb) set disassembly-flavor intel
	(gdb) disassemble main
	Dump of assembler code for function main:
	   0x000000000000091a <+0>:     push   rbp
	   0x000000000000091b <+1>:     mov    rbp,rsp
	   0x000000000000091e <+4>:     sub    rsp,0x10
	   0x0000000000000922 <+8>:     mov    DWORD PTR [rbp-0x4],edi
	   0x0000000000000925 <+11>:    mov    QWORD PTR [rbp-0x10],rsi
	   0x0000000000000929 <+15>:    mov    eax,0x0
	   0x000000000000092e <+20>:    call   0x8d8 <header>
	   0x0000000000000933 <+25>:    mov    eax,0x0
	   0x0000000000000938 <+30>:    call   0x82f <set_timer>
	   0x000000000000093d <+35>:    mov    eax,0x0
	   0x0000000000000942 <+40>:    call   0x87d <get_key>
	   0x0000000000000947 <+45>:    mov    eax,0x0
	   0x000000000000094c <+50>:    call   0x8ac <print_flag>
	   0x0000000000000951 <+55>:    mov    eax,0x0
	   0x0000000000000956 <+60>:    leave  
	   0x0000000000000957 <+61>:    ret    
	End of assembler dump.
	(gdb) break main
	Breakpoint 1 at 0x91e
	(gdb) run
	Starting program: /home/ccajero-picoctf/NeedForSpeed/need-for-speed 
	warning: Error disabling address space randomization: Operation not permitted
	[Thread debugging using libthread_db enabled]
	Using host libthread_db library "/lib/x86_64-linux-gnu/libthread_db.so.1".
	
	Breakpoint 1, 0x0000562f4dc0091e in main ()
	(gdb) call (int) get_key()
	Creating key...
	Finished
	$3 = 9
	(gdb) call (int) print_flag()
	Printing flag:
	PICOCTF{Good job keeping bus #24c43740 speeding along!}
	$4 = 56

------------------------------------


## Notas adicionales

## Referencias
