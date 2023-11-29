## Objetivo
Can you get the flag?Download this [binary](https://artifacts.picoctf.net/c/87/gdbme).Here's the test drive instructions:

- `$ chmod +x gdbme`
- `$ gdb gdbme`
- `(gdb) layout asm`
- `(gdb) break *(main+99)`
- `(gdb) run`
- `(gdb) jump *(main+104)`
## Solución

	ccajero-picoctf@webshell:~/GBDTestDrive$ chmod +x gdbme 
	ccajero-picoctf@webshell:~/GBDTestDrive$ gdb gdbme
	
	(gdb) 
	(gdb) break *(main+99)
	Breakpoint 1 at 0x132a
	(gdb) run
	
	Breakpoint 1, 0x000055c7d129432a in main ()
	(gdb) jump *(main+104)
	Continuing at 0x55c7d129432f.
	picoCTF{d3bugg3r_dr1v3_7776d758}
	[Inferior 1 (process 268) exited normally]

## Notas adicionales

## Referencias
