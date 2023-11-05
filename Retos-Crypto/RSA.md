c - texto cifrado 
m - texto plano
p, q - números primos
e - llave publica 65537
d - Llave privada
t - totient
n - modulo

n = p * q
t = (p - 1) * (q - 1)
d = e mod-inverso t (pow(e, -1, t))

Encriptar
____
c = m^e  *mod* n

Desencriptar
__________________________________
m = t^d *mod* n 
