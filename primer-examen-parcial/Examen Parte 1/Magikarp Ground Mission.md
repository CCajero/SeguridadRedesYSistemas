### Magikarp Ground Mission

	ccajero-picoctf@webshell:~$ ssh ctf-player@venus.picoctf.net -p 57949
	ctf-player@pico-chall$ ls
	1of3.flag.txt  instructions-to-2of3.txt
	ctf-player@pico-chall$ cat 1of3.flag.txt 
	picoCTF{xxsh_
	ctf-player@pico-chall$ cat instructions-to-2of3.txt 
	Next, go to the root of all things, more succinctly `/`
	ctf-player@pico-chall$ cd /
	ctf-player@pico-chall$ ls
	2of3.flag.txt  bin  boot  dev  etc  home  instructions-to-3of3.txt  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
	ctf-player@pico-chall$ cat 2of3.flag.txt 
	0ut_0f_\/\/4t3r_
	ctf-player@pico-chall$ cat instructions-to-3of3.txt 
	Lastly, ctf-player, go home... more succinctly `~`
	ctf-player@pico-chall$ cd ./home
	ctf-player@pico-chall$ cd ctf-player/
	ctf-player@pico-chall$ cat 3of3.flag.txt 
	21cac893}