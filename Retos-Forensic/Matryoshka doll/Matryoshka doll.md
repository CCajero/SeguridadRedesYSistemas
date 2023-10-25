## Objetivo
Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one? Image: [this](https://mercury.picoctf.net/static/5eb456e480e485183c9c1b16952c6eda/dolls.jpg)
## Solución
	binwalk --extract dolls.jpg
	 cd _dolls.jpg.extracted/base_images/
	 binwalk --extract 2_c.jpg
	 cd _2_c.jpg.extracted/base_images/
	 binwalk --extract 3_c.jpg
	 cd _3_c.jpg.extracted/base_images/
	 binwalk --extract 4_c.jpg
	 cd _4_c.jpg.extracted/base_images/

picoCTF{336cf6d51c9d9774fd37196c1d7320ff}	 

## Notas adicionales

## Referencias
