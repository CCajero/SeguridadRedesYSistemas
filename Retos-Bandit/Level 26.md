## Level 26
## Objetivo
Logging in to bandit26 from bandit25 should be fairly easy… The shell for user bandit26 is not **/bin/bash**, but something else. Find out what it is, how it works and how to break out of it.
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit25
	Password: p7TaowMYrmu23Ol8hiZh9UvD0O9hpx8d
	
## Solución
	cat /etc/passwd | grep bandit26
	cat /usr/bin/showtext
	cat bandit26.sshkey
	ssh -i bandit26.sshkey bandit26@localhost -p 2220 (reducir pantalla y presionar tecla v)
	:e /etc/bandit_pass/bandit26
	:qa

	c7GvcKlw9mC7aUQaPx7nwFstuAIBw1o1
## Notas adicionales

## Referencias