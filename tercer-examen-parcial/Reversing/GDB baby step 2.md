## Descripción
Can you figure out what is in the `eax` register at the end of the `main` function? Put your answer in the picoCTF flag format: `picoCTF{n}` where `n` is the contents of the `eax` register in the decimal number base. If the answer was `0x11` your flag would be `picoCTF{17}`.Debug [this](https://artifacts.picoctf.net/c/520/debugger0_b).
## Solución

	info functions
	disassemble main
	break main
	layout asm
	run
	break *0x401142
	c
	info registers rip
	print/d $eax

picoCTF{307019}
