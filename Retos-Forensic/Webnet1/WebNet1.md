## Objetivo
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/picopico.key). Recover the flag.
## Solución
Abrimos el paquete con whireshark
Seleccionamos edición-preferencias-TLS y cargamos la llave

Archivo-Exportar Objetos-HTTP
Exportamos la imagen.jpg
Abrimos la imagen en modo texto y buscamos pico.

picoCTF{honey.roasted.peanuts}

----------------------------------

ssldump -r capture.pcap -k picopico.key -d | grep pico -A 2 -B 2
## Notas adicionales

## Referencias
