# darkmode-ejercicio

En este ejercicio el estado de mi aplicacion debera manejar el cambio de light mode a darkmode.
Para poder hacerlo funcionar deberemos:

1- Crear un modelo que tenga un atributo booleano llamado darkmode y un atributo string llamado text

2- Crear un pinia store que implemente el modelo anterior, definir como estado inicial:
- darkmode: false
- text: "LightMode"

3- Crear una accion que cambie el estado a:
- darkmode: true
- text: "DarkMode"

Una vez creado el store