# 🧹 Calidad de Datos
## Descripción
Este informe analiza la calidad de los datos, problemas encontrados y estrategias de limpieza.
- Análisis de valores nulos, inconsistencias y sesgos.
- Métodos utilizados para mejorar la calidad del dataset.

Para este ejercicio se utilizo los siguientes pasos para la limpieza de datos:

- Reemplazar valores NaN por vacíos.​
- Crear el campo de cantidad de noches en formato numérico ​(Antes: '41 noches').​
- Convertir el campo de Fecha de hospedaje en formato Date (Antes: 'octubre de ​2024').​
- Convertir el campo Fecha de reseña en formato Date (Antes: 31 de julio de 2023)​
- Convertir el valor de Calificación en formato Float (Antes: '9,0').​
- Filtrar el campo acomodación y países para que no tome valores vacíos.

**Cantidad de registros iniciales:** 438.213

**Cantidad de datos finales:** 19.818

Desde el equipo de ingeniería de datos se sugiere :​

- Mejora en el formulario de registro de encuesta de reseñas ya que se evidencia campos de país y acomodación no diligenciados.​
- Incentivos para que los usuarios diligencien este formato y poder obtener mayor entrada de datos.
