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
### Conclusión de la consulta
La consulta estuvo relativamente fácil por su simpleza. No surgieron problemas en la creación de esté código. 
## Consulta 2: Tabletas con más de 2 GB de RAM
## Consulta 3: Discos duros entre 32 GB y 512 GB
## Consulta 4: Cantidad de plataformas ASUS
## Consulta 5: Laptops con más de 4 GB y menos de 512 GB de disco duro
