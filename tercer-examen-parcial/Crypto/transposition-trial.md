## Descripción
Our data got corrupted on the way here. Luckily, nothing got replaced, but every block of 3 got scrambled around! The first word seems to be three letters long, maybe you can use that to recover the rest of the message.Download the corrupted message [here](https://artifacts.picoctf.net/c/193/message.txt).

## Solución
	txt = open('message.txt').read() 
	flag = ' ' 
	i = 0 
	while (i < len(txt)):
	        flag = flag + txt[i+2] + txt[i] + txt[i+1]
	        i = i + 3
	print(flag)
	The flag is picoCTF{7R4N5P051N6_15_3XP3N51V3_A9AFB178}
## Notas adicionales

## Referencias
