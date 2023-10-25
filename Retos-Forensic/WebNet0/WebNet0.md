## Objetivo
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/picopico.key). Recover the flag.
## Solución
Abrimos el paquete
Seleccionamos edición-preferencias-TLS y cargamos la llave
Buscamos en los detalles de paquete: picoCTF

Pico-Flag: picoCTF{nongshim.shrimp.crackers}

-----------------------------------
comando: ssldump

ssldump -r capture.pcap -k picopico.key -d 

ssldump -r capture.pcap -k picopico.key -d  | pico -A 2 -B 2
## Notas adicionales

## Referencias
