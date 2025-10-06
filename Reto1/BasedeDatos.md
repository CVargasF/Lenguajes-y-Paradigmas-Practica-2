# **Base de Datos**
## Datos relevantes
Para la base de datos vamos a necesitar tener que ver que datos relevantes nos pide. Los datos que nos otorgan son para la información general de una plataforma computacional (Tableta, PC, Laptop). Los datos que son relevantes para este primer reto son:  
La marca de la plataforma  
El número serial del producto  
El año en el que se obtuvo  
La capacidad de RAM  
El manufactor de la CPU  
El número de núcleos en la CPU  
La capacidad del disco duro  
El tipo de plataforma  
El Manufactor de la tarjeta gráfica
El Video-Ram de la plataforma  
En total son 10 datos relevantes a cada plataforma.
## Estructura de dato
Los datos los vamos a componer como **hechos** para tener nuestra base de datos en Prolog.
El nombre de los hechos va ser "Plataforma", mientras que las variables que van a cargar van a ser todos los datos relevantes.  
La estructura quedaría como "plataforma(Marca, Número serial, Año, Capacidad Ram, Manufactor, Número de nucleos, Capacidad de disco duro, Tipo de plataforma, Manufactor de tarjeta gráfica, Capacidad de Video-Ram). "
## Creación de los datos
Lo primero que hay que ver son lo que nos piden directamente. La base de datos requiere un mínimo de 50 hechos. Para la creación de datos también se necesita considerar los problemas de adelante. Esto es porque no sirve tener consultas especificas, si no se pueden cumplir por falta de datos. Solo analizando la primera, se necesita tener almenos una CPU de AMD. Luego podemos pasar a la cuarta, que nos fuerza a tener por lo menos una plataforma de ASUS. Esto solo son las compañias. El resto de las entradas solo piden valores normales de RAM, capacidad de disco duro y año de adquisición. 
