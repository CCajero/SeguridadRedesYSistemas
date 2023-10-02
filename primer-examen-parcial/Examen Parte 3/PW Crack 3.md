Can you crack the password to get the flag?
Download the password checker here and you'll need the encrypted flag and the hash in the same directory too.
There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.

	ccajero-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/18/level3.py
	ccajero-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/18/level3.flag.txt.enc
	ccajero-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/18/level3.hash.bin
	ccajero-picoctf@webshell:~$ ls
	README.txt  level3.flag.txt.enc  level3.hash.bin  level3.py
	pos_pw_list = ["8799", "d3ab", "1ea2", "acaf", "2295", "a9de", "6f3d"]
	ccajero-picoctf@webshell:~$ python level3.py
	Please enter correct password for flag: 8799
	That password is incorrect
	ccajero-picoctf@webshell:~$ python level3.py
	Please enter correct password for flag: d3ab
	That password is incorrect
	ccajero-picoctf@webshell:~$ python level3.py
	Please enter correct password for flag: 1ea2
	That password is incorrect
	ccajero-picoctf@webshell:~$ python level3.py
	Please enter correct password for flag: 2295
	Welcome back... your flag, user:
	picoCTF{m45h_fl1ng1ng_6f98a49f}
