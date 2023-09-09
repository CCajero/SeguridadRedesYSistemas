## Level 15
## Objetivo
The password for the next level can be retrieved by submitting the password of the current level to **port 30001 on localhost** using SSL encryption.
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit15
	Password: jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt
	
## Solución
	openssl s_client -connect localhost:30001
	jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt

	JQttfApK4SeyHwDlI9SXGR50qclOAil1

## Notas adicionales

## Referencias