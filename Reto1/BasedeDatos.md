# **Base de Datos**
## Datos relevantes
Para la base de datos vamos a necesitar tener que ver que datos relevantes nos pide. Los datos que nos otorgan son para la información general de una plataforma computacional (Tableta, PC, Laptop). Los datos que son relevantes para este primer reto son:  
  1. La marca de la plataforma  
  2. El número serial del producto  
  3. El año en el que se obtuvo  
  4. La capacidad de RAM  
  5. El manufactor de la CPU  
  6. El número de núcleos en la CPU  
  7. La capacidad del disco duro  
  8. El tipo de plataforma  
  9. El Manufactor de la tarjeta gráfica
  10. El Video-Ram de la plataforma  

En total son 10 datos relevantes a cada plataforma.
## Estructura de dato
Los datos los vamos a componer como **hechos** para tener nuestra base de datos en Prolog.
El nombre de los hechos va ser "Plataforma", mientras que las variables que van a cargar van a ser todos los datos relevantes.  
La estructura quedaría como "plataforma(Marca, Número serial, Año, Capacidad Ram, Manufactor, Número de nucleos, Capacidad de disco duro, Tipo de plataforma, Manufactor de tarjeta gráfica, Capacidad de Video-Ram). "  
<img width="1112" height="73" alt="Plataforma1" src="https://github.com/user-attachments/assets/de6c4c5d-b375-4a9e-bdb1-3c1320cda9bc" />
<sup>Imagen de un comentario dentro del programa con la estructura</sup>
## Requerimientos de los datos
Lo primero que hay que ver son lo que nos piden directamente. La base de datos requiere un mínimo de 50 hechos. Para la creación de datos también se necesita considerar los problemas de adelante. Esto es porque no sirve tener consultas especificas, si no se pueden cumplir por falta de datos. Solo analizando la primera, se necesita tener almenos una CPU de AMD. Luego podemos pasar a la cuarta, que nos fuerza a tener por lo menos una plataforma de ASUS. Esto solo son las compañias. El resto de las entradas solo piden valores normales de RAM, capacidad de disco duro y año de adquisición. Pasando a las variables que sean números, la primera necesita tener computadores después y antes de 2021. Tienen que haber por lo menos una tableta con más de 2GB de RAM instalado. Tiene que existir plataformas que tengan entre 32GB y 512 GB de disco duro. Y por ultimo, tiene que existir una laptop con más de 4GB de RAM y ménos de 512GB de disco duro. 
## Creación de los datos
Ya con estos datos construimos la base de datos. Hay que remarcar que los datos NO son reales, no se basan en ninguna compañia y pueden tender a error. Esto es porque sería extremadamente tedioso buscar 500 datos mínimos enves de inventarlos (cada plataforma que se añade son 10 datos). Los datos son relativamente facil de ingresar, aunque es un proceso extenso por la cantidad de información que se debe poner. Al final, se creo un total de 56 plataformas. Todas tienen un diferente número serial, este es la manera de identificar una por una.  
<img width="1228" height="496" alt="plataforma2" src="https://github.com/user-attachments/assets/c0c1bb85-22b7-4f8c-bd12-4de9a7ad7fff" />
<sup>Imagen de una parte de los datos ingresados</sup>
