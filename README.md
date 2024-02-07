# VIDEOCLUB (para nostálicos)
![Static Badge](https://img.shields.io/badge/PostgreSql-005C53)


## Práctica de Modelado y SQL
En este repositorio se encuentra el archivo `videoclub_ricardo_lopez.sql` que contiene las consultas necesarias para crear y manipular una base de datos un videoclub,
asi como el archivo .drawio  que se utiliza para la documentación del proyecto.


- Necesito registrar los socios del videoclub. Al menos necesito su nombre y apellidos,
fecha de nacimiento, teléfono y su número de identificación (DNI, Pasaporte, o el nombre
que reciba en tu país) y nosotros le asignaremos un número de socio que usaremos para
hacer carnets.

- Necesito registrar la dirección de correspondencia de los socios para, eventualmente,
hacer campañas de publicidad, pero no es un requisito obligatorio que un socio nos de
esa información. Con el código postal, calle, número y piso es suficiente,
sobreentendemos que será de la misma ciudad donde está el videoclub.

- Necesito registrar las películas. Puedo tener más de una copia de cada una. De cada
película necesito registrar el título, año de publicación, género, director y sinopsis.

- Necesito saber a que socio le he prestado cada copia y cuando. Es decir, registrar la
fecha en la que se la ha llevado y la fecha de la devolución. Cuando una película no tiene
fecha de devolución, la consideramos prestada.

#### Consultas finales
- Que películas están disponibles para alquilar en este momento (no están
prestadas). Necesito el título y el número de copias disponibles
- Cual es el género favorito de cada uno de mis socios para poder recomendarle
películas cuando venga. Necesito el número de socio, nombre y género favorito.