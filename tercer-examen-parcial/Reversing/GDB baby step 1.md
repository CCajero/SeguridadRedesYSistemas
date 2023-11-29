## Descripción

## Solución
	(gdb) disas main
	Dump of assembler code for function main:
	   0x0000000000001129 <+0>:     endbr64 
	   0x000000000000112d <+4>:     push   %rbp
	   0x000000000000112e <+5>:     mov    %rsp,%rbp
	   0x0000000000001131 <+8>:     mov    %edi,-0x4(%rbp)
	   0x0000000000001134 <+11>:    mov    %rsi,-0x10(%rbp)
	   0x0000000000001138 <+15>:    mov    $0x86342,%eax
	   0x000000000000113d <+20>:    pop    %rbp
	   0x000000000000113e <+21>:    ret    
	End of assembler dump.

Nos fijamos en la línea 15
picoCTF{549698}