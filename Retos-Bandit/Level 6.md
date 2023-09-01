# Level 6

## Objetivo
The password for the next level is stored in a file somewhere under the **inhere** directory and has all of the following properties:
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit5
	Password: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
## Solución
	cd inhere
	ls
	find . -readable -type f -size 1033c
	cat ./maybehere07/.file2
	
	P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
## Notas adicionales
El comando find busca
La opción -readble especifica ser leíble
La opción -size especifica tamaño
La opción -file especifica tipo archivo
## Referencias