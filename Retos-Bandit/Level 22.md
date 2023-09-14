## Level 22
## Objetivo
A program is running automatically at regular intervals from **cron**, the time-based job scheduler. Look in **/etc/cron.d/** for the configuration and see what command is being executed.
## Datos de acceso
	Server: bandit.labs.overthewire.org
	User: bandit21
	Password: NvEJF7oVjkddltPSrdKEFOllh9V1IBcq
	
## Solución
	cat /etc/crontab
	ls -la /etc/cron.d
	ls /etc/cron.d
	cat /etc/cron.d/cronjob_bandit22
	cat /usr/bin/cronjob_bandit22.sh
	cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv

	WdDozAdTM2z9DiFEQ2mGlwngMfj4EZff
## Notas adicionales

## Referencias