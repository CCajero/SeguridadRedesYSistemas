## Level 10
## Objetivo
The password for the next level is stored in the file **data.txt** in one of the few human-readable strings, preceded by several ‘=’ characters.
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit9
	Password: EN632PlfYiZbn3PhVK3XOGSlNInNE00t
## Solución
	ls
	file data.txt
	strings data.txt | grep ==

	G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
## Notas adicionales
El comando strings encuentra e imprime cadenas de texto incrustadas en archivos binarios
## Referencias