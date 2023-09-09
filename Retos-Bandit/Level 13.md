## Level 13
## Objetivo
The password for the next level is stored in the file **data.txt**, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work using mkdir. For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv (read the manpages!)
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit12
	Password: JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
## Solución
	xxd -r data.txt | file -
	xxd -r data.txt | zcat |file -
	xxd -r data.txt | zcat | bzcat |file -
	xxd -r data.txt | zcat | bzcat | zcat |file -
	xxd -r data.txt | zcat | bzcat | zcat | tar xO | file -
	xxd -r data.txt | zcat | bzcat | zcat | tar xO | tar xO | file -
	xxd -r data.txt | zcat | bzcat | zcat | tar xO | tar xO | bzcat |file -
	xxd -r data.txt | zcat | bzcat | zcat | tar xO | tar xO | bzcat | tar xO | file -
	xxd -r data.txt | zcat | bzcat | zcat | tar xO | tar xO | bzcat | tar xO | zcat | file -
	xxd -r data.txt | zcat | bzcat | zcat | tar xO | tar xO | bzcat | tar xO | zcat
	
	wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
	
	
## Notas adicionales

## Referencias