# Level 7

## Objetivo
The password for the next level is stored **somewhere on the server** and has all of the following properties:
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit6
	Password: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
## Solución
	ls -la
	find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
	cat /var/lib/dpkg/info/bandit7.password

	z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
## Notas adicionales
El comando find busca
La opción -user especifica el usuario
La opción -group especifica el grupo
La opción -size especifica tamaño

## Referencias