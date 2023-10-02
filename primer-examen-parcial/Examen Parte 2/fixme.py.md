Fix the syntax error in this Python script to print the flag.
Download Python script

	ccajero-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/25/fixme1.py
	ccajero-picoctf@webshell:~$ python fixme1.py 
	  File "/home/ccajero-picoctf/fixme1.py", line 20
    print('That is correct! Here\'s your flag: ' + flag)
	IndentationError: unexpected indent
	ccajero-picoctf@webshell:~$ nano fixme1.py 
	ccajero-picoctf@webshell:~$ python fixme1.py 
	That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_6a476c8f}
	