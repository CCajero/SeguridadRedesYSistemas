## Objetivo
I've hidden a flag in this file. Can you find it? [Forensics is fun.pptm](https://mercury.picoctf.net/static/9a7436948cc502e9cacf5bc84d2cccb5/Forensics%20is%20fun.pptm)
## Solución
Descargamos el archivo.
Hacemos unzip al archivo unzip Forensics\ is\ fun.pptm 

	ccajero-picoctf@webshell:~/macro$ unzip Forensics\ is\ fun.pptm
	ccajero-picoctf@webshell:~/macro$ cd ppt/slideMasters/
	ccajero-picoctf@webshell:~/macro/ppt/slideMasters$ cat hidden
	ccajero-picoctf@webshell:~/macro/ppt/slideMasters$cat hidden | tr -d ' ' | base64 -d

Traducimos el contenido del archivo de base 64
picoCTF{D1d_u_kn0w_ppts_r_z1p5}


## Notas adicionales
Una macro **es una serie de comandos e instrucciones que se agrupan de forma conjunta como un mismo comando para completar una tarea automáticamente**.
## Referencias
