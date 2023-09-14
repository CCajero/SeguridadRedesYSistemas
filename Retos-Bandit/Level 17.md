## Level 17
## Objetivo
The credentials for the next level can be retrieved by submitting the password of the current level to **a port on localhost in the range 31000 to 32000**. First find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit16
	Password: JQttfApK4SeyHwDlI9SXGR50qclOAil1
	
## Solución
	nmap -p 31000-32000 localhost

	notepad llave.txt
	type llave.txt
	ssh -i llave.txt
	bandit17@bandit.labs.overthewire.org -p2220
	cat /etc/bandit_pass/bandit17

	VwOSWtCA7lRKkTfbr2IDh6awj9RNZM5e
## Notas adicionales
El comando nmap sirve para exploración de red y auditoría de seguridad.
## Referencias