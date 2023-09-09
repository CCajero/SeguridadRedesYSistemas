## Level 11
## Objetivo
The password for the next level is stored in the file **data.txt**, which contains base64 encoded data
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit10
	Password: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
## Solución
	ls
	cat data.txt
	cat data.txt | base64 -d

	6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
## Notas adicionales
La opción -d del comando base64 descifra el texto.
## Referencias