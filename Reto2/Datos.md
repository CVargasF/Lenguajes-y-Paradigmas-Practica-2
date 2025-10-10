# **EJERCICIO 4.0**
El objetivo de este codigo es crear un sistema que planifique rutas de viajes entre ciaudades con las funciones:
1. Mostrar rutas directas con escalas
2. Calcular rutas óptimas 
3. Filtrar por horario 
4. Mostrar alternativas

# **CONCEPTOS**

1. Las rutas tienen: origen, destino, medio de transporte, hora salida/llegada, costo y disponibilidad
2. Las rutas deben tener coherencia de orden, que el segundo viaje salga despues del primero 
3. Usar busqueda y comparación para que el programa retorne las mejores opciones
4. Mostrar resultados

# **¿QUÉ HACE EL CÓDIGO?**
Basicamente el codigo funciona como un google flights en prolog que encuentra la mejor manera de viajar entre ciudades en avion o en bus, sus horarios, costos y disponibilidad de todas las rutas 

# **RESULTADOS**
1. Muestra todas las rutas disponibles segun tu lugar de origen y tu destino con mostrar_todas_rutas
2. Busca las rutas mas optimas del viaje que quiere realizar el usuario con ruta_mas_rapida
3. Selecciona las rutas según el intervalo de tiempo que necesite el usuario, por ejemplo, retorna todos lo viajes entre las 6am y 10 am, esto con rutas_por_horario
4. Muestra las rutas alternativas en caso de que no haya vuelo directo a la ciudad que el usuario desee, con sugerir_rutas_alternativas


# **PROBLEMAS Y SOLUCIONES**
-Problema 1: tuve problemas con el orden en que se tomaban los viajes, en donde el segundo viaje salia antes que el primero, lo solucioné agregando validación temporal para tener coherencia con los horarios.
-Problema 2: el programa a veces repetia la ciudad por ej: Bogotá → Bogotá → Medellín, así que implementé restricciones para evitar que la escala, origen y destino sean la misma ciudad.   
-Problema 3: tuve muchos errores de sintaxis, los corregí repasando una y otra vez el codigo. 


# **CODIGO**
<img width="860" height="928" alt="image" src="https://github.com/user-attachments/assets/87db27a5-9e67-45df-af49-3153e015c811" />
<img width="916" height="829" alt="image" src="https://github.com/user-attachments/assets/fdad24dd-e8a1-4443-aa28-c7f272c29982" />
<img width="931" height="882" alt="image" src="https://github.com/user-attachments/assets/ddab5afb-1ba7-44aa-848d-3fb2c767e0ab" />
<img width="932" height="890" alt="image" src="https://github.com/user-attachments/assets/68e00b7f-ed48-4900-a695-2cb832c4d5b4" />
<img width="936" height="814" alt="image" src="https://github.com/user-attachments/assets/bdb4e6cc-da8a-400c-8b5b-178a3efd4275" />
<img width="977" height="812" alt="image" src="https://github.com/user-attachments/assets/ebfca211-eebe-4a7a-93ed-84c74ebeb6c2" />
<img width="952" height="921" alt="image" src="https://github.com/user-attachments/assets/b76db6ff-e130-44e2-8d7d-24023ae1511b" />
<img width="908" height="463" alt="image" src="https://github.com/user-attachments/assets/ae9481a4-30cf-4af0-a467-a6448cedae81" />

# **CONSULTAS**
Mostrar todas las rutas

<img width="870" height="296" alt="image" src="https://github.com/user-attachments/assets/6c9099aa-60a9-4686-a71d-e1842dce059e" />

La ruta mas rapida 

<img width="530" height="234" alt="image" src="https://github.com/user-attachments/assets/d722be09-f8d2-4435-9350-2cb17f8e2834" />

La ruta mas barata 

<img width="499" height="258" alt="image" src="https://github.com/user-attachments/assets/7690638e-3fe4-471f-9008-14800d42a810" />

Las rutas por horario determinado 

<img width="563" height="229" alt="image" src="https://github.com/user-attachments/assets/f43da27f-da47-41ec-9c0a-7ff9f9ac430b" />

Las rutas alternativas

<img width="764" height="201" alt="image" src="https://github.com/user-attachments/assets/8f886f22-c561-464a-a443-aa67f2aa5abd" />

Opción extra 

<img width="624" height="372" alt="image" src="https://github.com/user-attachments/assets/1794c28b-df45-499a-b325-8cd1f3db9d27" />


