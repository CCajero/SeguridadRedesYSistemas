# Level 8

## Objetivo
The password for the next level is stored in the file **data.txt** next to the word **millionth**
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit7
	Password: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
## Solución
	ls
	wc data.txt
	grep millionth data.txt
	cat data.txt | grep millionth

	TESKZC0XvTetK0S9xNwm25STk5iWrBvP
## Notas adicionales
El comando wc permite realizar conteos
El comando grep sirve para buscar un patrón en un archivo
El | sirve para piping
## Referencias