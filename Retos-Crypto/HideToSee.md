## Objetivo

## Solución
	ccajero-picoctf@webshell:~/HidetoSee$ steghide --extract -sf atbash.jpg 
	Enter passphrase: 
	wrote extracted data to "encrypted.txt".
	ccajero-picoctf@webshell:~/HidetoSee$ cat encrypted.txt 
	krxlXGU{zgyzhs_xizxp_92533667}

Desciframos con AtBash Cipher
picoCTF{atbash_crack_92533667}
## Notas adicionales

## Referencias
https://gchq.github.io/CyberChef/