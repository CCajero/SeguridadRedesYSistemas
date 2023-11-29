## Objetivo
We have recovered a [binary](https://jupiter.challenges.picoctf.org/static/31c9b832d036a10daeef52d8b4290ef0/rev) and a [text file](https://jupiter.challenges.picoctf.org/static/31c9b832d036a10daeef52d8b4290ef0/rev_this). Can you reverse the flag.
## Solución

	txt = open('rev_this').read()
	print(txt)
	flag=''
	
	for i in range(8,len(txt)-1):
	        if i & 1 == 0:
	                flag += chr(ord(txt[i]) - 5)
	        else:
	                flag += chr(ord(txt[i]) + 2)
	print (flag)

	picoCTF{w1{1wq85jc=2i0<}
	r3v3rs37ee84d27
## Notas adicionales

## Referencias
