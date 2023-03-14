# Práctica 2 - Manual Técnico

## MODULO ADMINISTRADOR
### ALGORITMO PARA AGREGAR USUARIO
Primero debemos de entender lo que sucede a nivel de maquina al momento de almacenar un usuario: <br>
<img>
<img src="./Imagenes/struct1.png" alt="drawing" style="width:50px;"/>

Como podemos ver tenemos <br>
Nombre -> 16 bytes<br>
Apodo -> 10 bytes<br>
Password -> 10 bytes<br>
Credito -> 2 bytes<br>
Por lo tanto este struct tendrá una dimensión total de 38 bytes dentro de la memoria EEPROM<br>

Aquí surge un problema, ya que los usuarios no será lo único que almacenera nuestra EEPROM, en esta también tendremos: <br>



