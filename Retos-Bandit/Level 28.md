## Level 28
## Objetivo
There is a git repository at `ssh://bandit27-git@localhost/home/bandit27-git/repo` via the port `2220`. The password for the user `bandit27-git` is the same as for the user `bandit27`.

Clone the repository and find the password for the next level.
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit27
	Password: YnQpBuifNMas1hcUFk70ZmqkhUU2EuaS
	
## Solución
	mktemp -d
	cd /tmp/tmp.8cMLNqxJpB
	git clone ssh://bandit27-git@localhost:2220/home/bandit27-git/repo

	AVanL161y9rsbcJIsFHuw35rjaOM19nR
## Notas adicionales

## Referencias
	