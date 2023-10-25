## Objetivo
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/483e50268fe7e015c49caf51a69063d0/capture.pcap). Recover the flag.
## Solución

Abrimos el archivo de paquetes en whireshark.
Vemos que en la secuencia 32 está 'start' y en la 60 está 'end' y ambos comparten el puerto destino 22
Nos salen varios paquetes y analizamos el puerto origen, donde después del 5 los números se tendrán que decodificar para obtener la bandera.

picoCTF{p1LLf3r3d_data_v1a_st3g0}
## Notas adicionales

## Referencias
