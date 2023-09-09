## Level 14
## Objetivo
The password for the next level is stored in **/etc/bandit_pass/bandit14 and can only be read by user bandit14**. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. **Note:** **localhost** is a hostname that refers to the machine you are working on
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit13
	Password: wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
	
## Solución
	ls
	ssh -i sshkey.private bandit14@localhost -p 2220
	cat /etc/bandit_pass/bandit14
	exit

	fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq
## Notas adicionales

## Referencias