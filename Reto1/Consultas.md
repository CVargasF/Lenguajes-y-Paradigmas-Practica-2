# **Consultas**
Hay un total de 5 consultas que el usuario tiene que poderle hacer a la base de datos.
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

Ya que aclaramos los datos de entrada podemos ir construyendo el proceso necesario.  

<img width="906" height="178" alt="potencials" src="https://github.com/user-attachments/assets/5e4e0723-afe2-40bf-acef-ce8b33dc931b" />  



### Prueba de la consulta

<img width="840" height="293" alt="cibsytaks" src="https://github.com/user-attachments/assets/536f92ee-c6ab-4327-9f6f-f30dc2c66700" />  

Esta consulta se vuelve extremadamente larga si tenemos un rango tan grande de valores. Para reducir la cantidad de resultados que se deben analizar, se toma un rango mucho menor de plataformas. 

<img width="538" height="121" alt="Reduccion" src="https://github.com/user-attachments/assets/55001079-809c-42ba-8f5e-65216717144c" />  

Solo cambiando algunas variables podemos comprobar si esta correcta la consulta.

<img width="526" height="217" alt="Encontrados" src="https://github.com/user-attachments/assets/1387743a-812e-433e-b876-6c0a74c63a8a" />

Con esta prueba podemos ver que todos los datos que nos paso la consulta original fueron correctos y tienen las capacidades de disco duro dentro del rango correcto. 
### Conclusión de la consulta
Esta consulta fue relativamente fácil por que es muy intuitiva. Añadir más filtros con equaciones especificas a un problema similar a los anteriores no presenta una gran dificultad. 
## Consulta 4: Cantidad de plataformas ASUS
La cuarta consulta requiere que el usuario pueda buscar el número de plataformas hechas por ASUS.  
### Analisis del problema
Esta consulta igual que la anterior presenta una solución similar en el que solo se considera un dato de importancia que es el manufactor del producto. En este caso es la compañia ASUS. Pero presenta un dato diferente que es encontrar la cantidad que hay. 
### Construcción de la consulta
Para esta consulta se tiene que hacer una operación que cuente elementos en una lista ya que podemos volver a utilizar findall para filtrar los elementos y ponerlos en una lista. Primero se crea la consulta y las variables que se utilizaran.  
<img width="435" height="17" alt="marcaresutlkar" src="https://github.com/user-attachments/assets/43999c2f-7981-463c-83d4-a0642db0d7ea" />  

Despues construimos el segmento que encuentra todos los elementos que sean creados por el manufactor especificado. Esto se hace utilizand findall como en los problemas anteriores.
<img width="806" height="102" alt="marcalistaplataforma" src="https://github.com/user-attachments/assets/e24a8dee-5e21-48f9-b8a7-23c7e347aa94" />  

Hasta donde llevamos, solo tenemos la lista que necesitamos contar. Podemos utilizar una función externa para poder contar la cantidad de elementos de la lista. Esta función es una que agarra la lista y remueve la cabeza de la lista y añade 1 al equivalente de un contador de Java. 

<img width="981" height="60" alt="LongitudListas" src="https://github.com/user-attachments/assets/7f285457-f04f-4ec6-9213-5a77b375acce" />  

Ya con esta función creada, la implementamos a la consulta que nos entrega una lista y ingresamos la lista que nos saca como el ingreso a la función que cuenta.

<img width="831" height="111" alt="encontrandocantidad" src="https://github.com/user-attachments/assets/2e4fbb28-8230-40dd-9e8b-2753ec33d452" />  

### Prueba de la consulta
Para esta consulta no se necesita mucha evidencia para saber si funciona correctamente. Simplemente analizas si la lista que tira el programa sin añadir la función de conteo está correcta y luego miras si el conteo lo hizo bien. Aqui hay un ejemplo de esto.

<img width="818" height="230" alt="Resultados" src="https://github.com/user-attachments/assets/d8def971-b847-4d1d-a781-721cbed322f8" />  

### Conclusión de la consulta
Este problema trae mucha más construcción por que requiere una funcion externa que no se a utilizado hasta ahora. No fue complicado crear la función de contar elementos, fue un tema tocado en clase y no debería presentar ninguna dificultad. Afuera de eso, el programa corre correctamente y es simple en entenderlo.
## Consulta 5: Laptops con más de 4 GB y menos de 512 GB de disco duro
La ultima consulta requiere que el usuario pueda buscar cuantas laptops con más de 4GB de RAM y menos de 512GB de disco duro. 
### Analisis del problema
Este problema requiere 3 variables. Que tipo de plataforma se busca, el mínimo de RAM y el máximo de disco duro. Además, como es un problema similar al anterior se utiliza la ecuación anterior para contar unidades. 
### Construcción de la consulta
Esta consulta se puede armar al juntar conceptos anteriores, los valores mínimos y máximos, las listas, y contar las listas. Todo esto junto se convierte en la consulta siguiente.
<img width="780" height="186" alt="Final" src="https://github.com/user-attachments/assets/a5be3e0f-34f3-4519-b3aa-762f39cc3dcb" />

### Prueba de la consulta

### Conclusión de la consulta
Para ser la ultima, esta muy bien que utilize todos los conceptos previamente utilizados y los teje en una sola consulta. Además de esto también puede ayudar a aclarar conceptos ya que muestran que pueden tener artos filtros uno encima de otro.
