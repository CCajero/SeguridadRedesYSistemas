## Objetivo
In RSA, a small `e` value can be problematic, but what about `N`? Can you decrypt this? [values](https://mercury.picoctf.net/static/38f30029ab93478310e906d3d084a4c1/values)
## Solución
	ccajero-picoctf@webshell:~/mindYourpPandQs$ wget https://mercury.picoctf.net/static/38f30029ab93478310e906d3d084a4c1/values
		ccajero-picoctf@webshell:~/mindYourpPandQs$ python3
		Python 3.10.6 (main, Aug 10 2022, 11:40:04) [GCC 11.3.0] on linux
		Type "help", "copyright", "credits" or "license" for more information.
	c = 240986837130071017759137533082982207147971245672412893755780400885108149004760496
	n = 831416828080417866340504968188990032810316193533653516022175784399720141076262857
	e = 65537
	p = 1593021310640923782355996681284584012117
	q = 521911930824021492581321351826927897005221
	t = (p-1)*(q-1)
	d = pow(e,-1,t)
	m = pow(c,d,n)
	m
	13016382529449106065927291425342535437996222135352905256639592405461024281868413
	bytes.fromhex(hex(m)[2:]).decode()
	'picoCTF{sma11_N_n0_g0od_23540368}'

## Notas adicionales
Se utiliza con un valor de n pequeño.
## Referencias
http://factordb.com/index.php?query=831416828080417866340504968188990032810316193533653516022175784399720141076262857