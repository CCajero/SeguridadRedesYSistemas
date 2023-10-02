
	ccajero-picoctf@webshell:~$ ls
	README.txt  flag  warm
	ccajero-picoctf@webshell:~$ chmod +x warm
	ccajero-picoctf@webshell:~$ ./warm
	Hello user! Pass me a -h to learn what I can do!
	ccajero-picoctf@webshell:~$ -h
	-bash: -h: command not found
	ccajero-picoctf@webshell:~$ ./warm -h
	Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_18788aaa}