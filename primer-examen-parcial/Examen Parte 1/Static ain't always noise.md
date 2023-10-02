	ccajero-picoctf@webshell:~$ wget https://mercury.picoctf.net/static/ff4e569d6b49b92d090796d4631a2577/static
	ccajero-picoctf@webshell:~$ wget https://mercury.picoctf.net/static/ff4e569d6b49b92d090796d4631a2577/ltdis.sh
	ccajero-picoctf@webshell:~$ ./static
	-bash: ./static: Permission denied
	ccajero-picoctf@webshell:~$ chmod +x static
	ccajero-picoctf@webshell:~$ ./static
	Oh hai! Wait what? A flag? Yes, it's around here somewhere!
	ccajero-picoctf@webshell:~$ ./ltdis.sh
	-bash: ./ltdis.sh: Permission denied
	ccajero-picoctf@webshell:~$ chmod +x ltdis.sh
	ccajero-picoctf@webshell:~$ ./ltdis.sh
	ccajero-picoctf@webshell:~$ ./ltdis.sh static
	ccajero-picoctf@webshell:~$ cat static.ltdis.strings.txt | grep pico
	1020 picoCTF{d15a5m_t34s3r_ccb2b43e}