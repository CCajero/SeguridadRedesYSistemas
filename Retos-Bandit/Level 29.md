## Objetivo
There is a git repository at `ssh://bandit28-git@localhost/home/bandit28-git/repo` via the port `2220`. The password for the user `bandit28-git` is the same as for the user `bandit28`.

Clone the repository and find the password for the next level.
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit28
	Password: AVanL161y9rsbcJIsFHuw35rjaOM19nR

## Solución
	 mktemp -d
	 cd /tmp/tmp.meRsIjtOIo
	 git clone ssh://bandit28-git@localhost:2220/home/bandit28-git/repo