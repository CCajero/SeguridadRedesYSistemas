# Level 9

## Objetivo
The password for the next level is stored in the file **data.txt** and is the only line of text that occurs only once
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit8
	Password: TESKZC0XvTetK0S9xNwm25STk5iWrBvP
## Solución
	ls
	cat data.txt | sort | uniq -u

	EN632PlfYiZbn3PhVK3XOGSlNInNE00t
## Notas adicionales
El comando sort ordena
El comando uniq muestra al no repetido
## Referencias