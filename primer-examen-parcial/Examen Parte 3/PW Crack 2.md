Can you crack the password to get the flag?
Download the password checker here and you'll need the encrypted flag in the same directory too.

	ccajero-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/14/level2.py
	ccajero-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/14/level2.flag.txt.enc
	ccajero-picoctf@webshell:~$ strings level2.flag.txt.enc 
	Vw1%B@
	RWS:Z
	ccajero-picoctf@webshell:~$ python level2.py
	ccajero-picoctf@webshell:~$ strings level2.py
	ccajero-picoctf@webshell:~$ python
	Python 3.10.6 (main, Aug 10 2022, 11:40:04) [GCC 11.3.0] on linux
	Type "help", "copyright", "credits" or "license" for more information.
	>>>chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39)
	'4ec9'
	>>>exit()
	ccajero-picoctf@webshell:~$ python level2.py 
	Please enter correct password for flag: 4ec9
	Welcome back... your flag, user:
	picoCTF{tr45h_51ng1ng_9701e681}