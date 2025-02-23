# 📊 Datos en el Proyecto
## Descripción
Este documento explica qué tipo de datos se pueden manejar dentro del proyecto y su estructura esperada.

La base de datos seleccionada consiste en el reporte de reseñas de Booking, en el que se puede observar un score, así como las tendencias principales tomadas en cuenta como: 

- **🌍 Demografía:** País del cual se está tomando la reseña.  
- **🏨 Tipo de acomodación:** Booking está dotado de diferentes acomodaciones.  
  Entre las principales, vemos apartamentos y habitaciones simples en hoteles.  
- **🛏️ Noches de hospedaje:** Cuántas noches tomó el usuario en la acomodación.  
- **📆 Fecha hospedaje:** Mes y año de correspondencia de la reserva.  
- **👥 Grupo de viaje:** Determina si el viaje fue realizado por una sola persona, pareja, familia, entre otros grupos.  
- **⭐ Reseña base:** Determinada por una única característica que resume la percepción del alojamiento.  
- **🔢 Calificación numérica:** Atributo de 1 a 10 suministrado por el usuario que se hospedó.  
- **💬 Comentarios:** Aspectos positivos y negativos.  
- **✅ Atributo de chequeo:** Determina si se realizó o no algún comentario.  


### Tipos de Datos 
El archivo base con el que se empezará el desarrollo del producto contiene una base de datos crudos sin procesar. El archivo requiere de una limpieza básica debido a la combinación de algunos atributos de difícil interpretación como “ñ” y tíldes. Así mismo se podrán determinar entradas inválidas que no aportan al desarrollo de la base y al posterior análisis y modelado del producto final. 

### Formato 
El archivo base es CVS que contiene información específica sobre acomodamientos en diferentes países del mundo, clasificados en acomodaciones, cantidad de noches, fecha de hospedaje, grupo hospedado, reseña general, y específica con calificación.  
