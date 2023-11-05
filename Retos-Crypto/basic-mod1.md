## Objetivo
We found this weird message being passed around on the servers, we think we have a working decryption scheme.Download the message [here](https://artifacts.picoctf.net/c/127/message.txt).Take each number mod 37 and map it to the following character set: 0-25 is the alphabet (uppercase), 26-35 are the decimal digits, and 36 is an underscore.Wrap your decrypted message in the picoCTF flag format (i.e. `picoCTF{decrypted_message}`)
## Solución
	
	 f= open('message.txt').read().split()
		flag = ''
		for c in f :
		        i = int(c)%37
		        if i>=0 and  i<=25:
		                flag+= chr(i+65)
		        elif i>=26 and  i<=35:
		                flag+= chr(i+22)
		        else:
		                flag+= "_"
		print(flag)
		
		picoCTF{R0UND_N_R0UND_79C18FB3}
## Notas adicionales

## Referencias
