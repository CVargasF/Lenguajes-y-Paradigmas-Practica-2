# **Consultas**
## Consulta 1: Procesadores de AMD después de 2021
La primera consutla que tenemos que crear requiere que el usuario pueda encontrar plataformas con marca AMD después de 2021. 
### Analisis del problema
Para poder resolver esta consulta tenemos que encontrar las variables que necesitamos. En este problema solo hay dos variables obias en el problema, la marca de la CPU y el año de obtención. Nos especifican que la plataforma tiene que ser después cierto año.
### Construcción de la consulta
Ya conociendo las variables que necesitamos y las especificaciones de cada una, podemos pasarlo a código. Lo primero en la construcción son las variables que ingrese el usuario en su busqueda. Estos son la marca de la CPU y desde que año en adelante se crearon las plataformas.  
<img width="447" height="23" alt="Capacidad" src="https://github.com/user-attachments/assets/73139acd-6900-435a-b177-5677e0190e66" />

Después de esto podemos ver como podemos utilizar recursividad a nuestra ventaja. Lo primero es filtrar las plataformas por las marcas de su CPU. Después de filtrar por eso encontramos como filtrar por un año especifico. Para esto convertimos el año de la plataforma en una variable dentro de la recursividad y decimos que el año de la plataforma tiene que ser mayor a el año ingresado por el usuario.  
<img width="697" height="56" alt="Cídgo1" src="https://github.com/user-attachments/assets/4dd570ae-2f40-4b13-b10d-5f3539b5ea2f" />

Aun le falta una parte a este problema, ya que solo ingresar este segmento solo te confirmara si **existen** pero no te especifica cuales son estas plataformas que existen. Para esto utilizamos una funcion de orden superior, esta siendo _findall_. Esta permite que el programa ponga en una lista variables que estén en este ciclo. Además de esto para funcionar correctamente, se le necesita aplicar un nombre a la lista. Y para eso se añade una variable de construcción, el nombre de la lista resultante.  
<img width="1250" height="88" alt="consulta1" src="https://github.com/user-attachments/assets/7950e8ae-478f-4a49-ae5f-71d1bc85a73f" />

### Prueba de la consulta
<img width="957" height="183" alt="ConsultaHecha1" src="https://github.com/user-attachments/assets/411c45cd-6ab2-4c79-a5cc-e66262a5513d" />  

En esta imagen podemos ver que correr el comando nos entrega la lista de códigos que pertenecen a los computadores que buscamos. Con una consulta que nos entrega los datos de cada uno podemos revisar caso por caso para estár seguros. Como la lista es extensa, solo se mostraran 3 de los datos y el resto se confirmara manualmente.  
<img width="815" height="145" alt="datos" src="https://github.com/user-attachments/assets/75b20064-ec4e-4947-a954-8a016bd28d27" />   

Como se puede apreciar, todos los datos siguen la regla de ser hechos después de 2021 y tener CPUs de marca amd.

### Conclusión de la consulta
La consulta estuvo relativamente fácil pero hubieron complicaciones en el proceso de intento y error. Hubo veces en la que surgieron errores por sintaxis y tomo un tiempo reconocer el error dentro del código. 
## Consulta 2: Tabletas con más de 2 GB de RAM
La segunda consulta pide que el usuario pueda encontrar tabletas con más de 2GB de RAM instalado.  
### Analisis del problema
Este problema es muy similar que el anterior, solo tiene dos variables que son vistas inmediatamente. La cantidad de RAM y el tipo de plataforma computacional. También podemos añadir el nombre de la lista a la lista de variables que lo componen.  
<img width="676" height="23" alt="consutlas" src="https://github.com/user-attachments/assets/01878630-3afe-4566-8b22-4b63d230cdcb" />  

### Construcción de la consulta
Este problema al ser tan similar al anterior, se puede acortar mucho el proceso ya que sabemos que elementos necesitamos.  
<img width="1237" height="50" alt="consulta2" src="https://github.com/user-attachments/assets/762748bd-42d0-485a-8d39-709dbfd51430" />  

La estructura se puede ver que es casi igual que el anterior. Utiliza _findall_ para encontrar hacer una lista con elementos que llenen los requerimientos. Estos siendo que tenga la plataforma especificada y que cumpla el requerimiento mínimo de RAM. 
### Prueba de la consulta
<img width="845" height="187" alt="datosnuevos" src="https://github.com/user-attachments/assets/e0dc6afb-88a1-48ff-8f7a-516c28b40a07" />  

La prueba de datos, igual que la anterior es exitosa. La lista de datos tiene un rango de 4 - 8 de RAM y son tabletas. 
### Conclusión de la consulta
Esta consulta estuvo relativamente fácil porque tiene una estructura muy similar a la anterior. No hubieron problemas probando ni creando la consulta.  

## Consulta 3: Discos duros entre 32 GB y 512 GB
La tercera consulta requiere que el usuario pueda buscar discos duros entre 32 GB y 512GB.  
### Analisis del problema
Este problema solo tiene una variable notable, el espacio de disco duro que tiene instalado cada plataforma. Esta variable se divide en 2 ya que se tiene que se debe poder elegir el mínimo y el máximo de disco duro instalado. La unica otra variable que se puede considerar es el nombre de la lista ya que se puede volver a utilizar la función findall. 
### Construcción de la consulta
Para construir esta consulta solo necesitamos 3 variables. El maximo de el mínimo de disco duro y el nombre de la lista resultante. 

<img width="877" height="23" alt="Capacdades" src="https://github.com/user-attachments/assets/ee185d81-ef79-4c48-a980-e0c8d9445223" />


### Prueba de la consulta
### Conclusión de la consulta

## Consulta 4: Cantidad de plataformas ASUS
## Consulta 5: Laptops con más de 4 GB y menos de 512 GB de disco duro
