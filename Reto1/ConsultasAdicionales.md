# **Consultas Adicionales**
Se tienen que implementar 4 consultas adicionales, estas tienen que ser consultas complejas. 
## Consulta 1: Qué computadores de marca Asus tienen más de 4 nucleos de CPU y menos de 6 video RAM?
### Construcción de la consulta
Esta consulta se ensambla con findall como las consultas que se hicieron en los problemas anteriores. 
<img width="928" height="35" alt="tipo123" src="https://github.com/user-attachments/assets/1e27b57a-eabe-4371-88a8-5f30515dff48" />  
La consulta tiene en total 4 variables además de la salida. El tipo de plataforma, la marca de la plataforma, la cantidad de núcleos minimos, y la máxima cantidad de video RAM. Para especificar, hay un máximo de video RAM, y un mínimo de nucleos en la CPU
<img width="962" height="157" alt="Consultapt2" src="https://github.com/user-attachments/assets/b01e183a-0042-44d4-9505-0ad148deb83e" />  
Luego se le añade el cuerpo a la consulta. Esta parte define que se tiene que buscar y lo que debe cumplir cada variable en la busqueda. Estos siendo que cumpla la limitación de video RAM y tambien cumpla el mínimo de nucleos de la CPU.  
### Prueba de la consulta
### Conclusión de la consulta



## Consulta 2: Cuántos computadores tienen una tarjeta grafica de Nvidia con más de 3 video RAM y más de 128 GB de disco duro?
### Construcción de la consulta
<img width="1006" height="31" alt="Consultaptyt123" src="https://github.com/user-attachments/assets/4d01e56e-e3aa-4761-b93a-12b99aba184b" />  
Esta consulta tiene 4 variables que tiene que ingresar el usuario, el disco duro minimo, el tipo de plataforma, la marca de la tarjeta grafica y el video RAM. Al final se pone el valor de 
a de la consulta.  
salid<img width="1038" height="190" alt="COnsultapartests12" src="https://github.com/user-attachments/assets/e2f489b5-2a85-4c95-a9ba-c5ad98e0e155" />  
El cuerpo de la consulta esta hecho de un find all que encuentra las plataformas computacionales filtrando por el tipo, la marca de la tarjeta gráfica, el minimo de video RAM y el mínimo de disco duro. 
### Prueba de la consulta
### Conclusión de la consulta


## Consulta 3: Encontrar que marcas de CPU tienen más de 4 núcleos en portatiles después de 2020
### Construcción de la consulta
<img width="840" height="22" alt="cuaucautklalñ ta" src="https://github.com/user-attachments/assets/6b516f57-271c-4b30-ac78-91c561dc430a" />
Este problema tiene 3 variables importantes, la cantidad mínima de nucleos en la CPU, el año mínimo y el tipo de plataforma.  
<img width="881" height="236" alt="cuartaratasos" src="https://github.com/user-attachments/assets/50425ed6-ced8-4b73-a068-db096e1b37d7" />  
La consulta utiliza findall para formar una lista que solo agarra las marcas de CPU de cada plataforma que sea hecha después del año especificado y sea del tipo pedido. Esto nos devuelve la lista con todas las marcas de CPU que necesitamos, pero el problema es que se repiten por cada plataforma extra que cumpla el requerimiento. Entonces se utiliza la función _sort_ para remover las copias en la lista.  
### Prueba de la consulta
### Conclusión de la consulta


## Consulta 4: Entre Hp y Asus, cual compañia tiene más computadores con más de 4 nucleos de CPU?
### Construcción de la consulta
<img width="820" height="28" alt="GUARDADOunico" src="https://github.com/user-attachments/assets/a332ecf0-4ccb-4b11-8d68-2803b17538a0" />
Para esta ultima consulta utilizamos 5 variables, el resultado, las dos plataformas que estaremos comparando, la cantidad de nucleos de la CPU, y el tipo. 
<img width="858" height="257" alt="ARREGLOAS" src="https://github.com/user-attachments/assets/a578a848-ed19-440f-853e-ed7a1f42c037" />
Ya con las variables definidas, construimos el cuerpo que va a requerir que se encuentre la cantidad de elementos en dos listas. Las listas tienen elementos de la compañia que se especifico. Luego de esto, ambas listas se agarran y se convierten en el número de elementos que cada una tiene. Al final pasan a una función externa para compararlas y mostrar el resultado. 
<img width="795" height="146" alt="formulaexterna" src="https://github.com/user-attachments/assets/9155c24d-06f1-4ab9-ac0d-ecf68ade4670" />  
Esta función solo es para mostrar el resultado mejor ya que no se puede mostrar en un solo valor de verdadero o falso.  
### Prueba de la consulta
### Conclusión de la consulta
