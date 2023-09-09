## Level 12
## Objetivo
The password for the next level is stored in the file **data.txt**, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit11
	Password: 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
## Solución
	ls
	cat data.txt
	cat data.txt | tr [a-zA-Z] [n-za-mN-ZA-M]
	
	JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
## Notas adicionales
El comando tr permite al Usuario definir explícitamente como estará compuesto el conjunto o bien provee de una colección de caracteres y conjuntos predefinidos.
## Referencias