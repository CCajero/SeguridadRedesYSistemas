## Objetivo
Check the admin scratchpad! `https://jupiter.challenges.picoctf.org/problem/63090/` or http://jupiter.challenges.picoctf.org:63090

## Datos de acceso

eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyIjoiQ3Jpc3RpYW4ifQ.iyj-b93DL-zmaK6UrITimUe3JdDVmV33WkktCWaYFsk
## Solución
Nos loggeamos con cualquier nombre
Buscamos el token jwt
Lo decodificamos
Dentro del token decodificado, cambiamos el nombre por "admin"
Cambiamos el token dentro de la página
Borramos la cookie

Utilizamos un ataque direccionario
	nos da de resultado la palabra ilovepico para firmar el token

Ponemos esa firma en el editor de tokens con usuario admin

picoCTF{jawt_was_just_what_you_thought_f859ab2f}
## Notas adicionales
JSON Web Token es un estándar abierto basado en JSON propuesto por IETF para la creación de tokens de acceso que permiten la propagación de identidad y privilegios o claims en inglés.
## Referencias
