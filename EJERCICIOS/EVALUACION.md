## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?
(valor 1.5)

* Asegurar el buen funcionamiento
* Retencion de la informacion
* Evitar perdida de datos
* Solucionar perdida de datos
* La segurudad de la base de datos

2. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)

* Instalar y gestionar la base de datos
* Dar soporte
* Diccionario de la base de datos
* Especificar restricciones
* Garantizar la disponibilidad de la base de datos

3. En una BD al usuario del sistema se le brindarán recursos para realizar diversas
operaciones sobre estos archivos, tales como: (valor 1.5)

* Efectuar cargos o abonos a cuentas
* Añadir cuentas nuevas
* Calcular el saldo de las cuentas
* Generar los extratos mensuales


4. ¿Qué es un Sistema de Información? (valor 1.5)

Conjunto de elementos orientandos al tratamiento y administracion de datos e informacion organizados y listos para su posterior uso

## Práctica 2.

2. Diseño de un modelo relacional

Objetivo: Representar desde un modelo entidad relación un problema


Ejercicio:

Tenemos que diseñar una base de datos sobre proveedores y disponemos de la siguiente
información:

Realiza el modelo entidad relación. (valor 6)

Tenemos esta información sobre una cadena editorial:

● La editorial tiene varias ***sucursales***, con su ***domicilio***, ***teléfono*** y un ***código*** de
sucursal.

● Cada sucursal tiene varios ***empleados***, de los cuales tendremos su ***nombre***,
***apellidos***, ***NIF*** y ***teléfono***. Un empleado trabaja en una única sucursal.

● En cada sucursal se publican varias ***revistas***, de las que almacenaremos su ***título***,
***número de registro***, ***periodicidad*** y ***tipo***.

● Una revista puede ser publicada por varias ***sucursales***.

● La editorial tiene ***periodistas*** (que no trabajan en las sucursales) que pueden
escribir artículos para varias revistas. Almacenaremos los mismos datos que para
los empleados, añadiendo su especialidad.

● También es necesario guardar las ***secciones fijas*** que tiene cada revista, que
constan de un ***título*** y una ***extensión***.

● Para cada ***revista***, almacenaremos información de cada ejemplar, que incluirá la
***fecha***, ***número de páginas*** y el ***número de ejemplares vendidos***.

![image](https://user-images.githubusercontent.com/101212784/169561540-fcbfc723-f3ae-4fb0-9ad3-bcfb1dd04fe7.png)

https://www.db-fiddle.com/f/6WfdDoiaLdnxyUe99nAHKV/0
https://www.db-fiddle.com/f/6WfdDoiaLdnxyUe99nAHKV/3
