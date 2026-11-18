# Análisis del rendimiento académico de estudiantes

**Proyecto Final**. **Autor:** Micaela Sanchez. **Curso:** Herramientas básicas para el análisis de datos. **Cohorte:** 2026
## Introducción

 Este proyecto lleva a cabo un profundo análisis sobre los factores que pueden ser determinantes para el rendimiento académico. Dicho analisis se lleva a cabo utilizando Python, Google Colab con realizaciones de visualizaciones con gráficos en Power BI.
 
 Dicho proyecto esta hecho a partir de un dataset con mas de 12.000 registros, en los cuales se efectuaron tareas de limpieza,analisis y visualizacion en Python y luego se realizo un Dashboard en Power BI.
 
## Objetivos del proyecto
 ¿Cuales son los factores que afectan al rendimiento academico?
 Esta investigación se basa en la búsqueda que factores que puedan afectar de forma negativa o positiva a la calificación de los estudiantes, también busca demostrar si el rendimiento académico de dichos alumnos es puramente determinado por sus acciones o si también se puede ver afectado por factores ajenos a estos, como el nivel educativo de los padres.
 
 Por medio de un proceso de análisis exploratorio, limpieza y visualizacion de datos se investigan puntos fundamentales para determinar o identificar dichos factores que podrian influir en la calificacion final, lo que nos otorgaria una vista mas profunda para poder identificarlos a tiempo y evitar que esto juegue en contra de los estudiantes.
 
## ¿Que buscamos en este analisis?

- Buscamos Encontrar factores determinantes para el rendimiento academico
 
- Analizar diferencias academicas entre generos y edades
 
- Ver la influencia a nivel academico del nivel educativo de los padres

- Determinar si las horas de estudio son determinantes
 
## Fuente de los datos utilizados 

 Fuente: Simulado en Python(dataset generado para la practica)
 
 Formato: CSV con 6 variables principales 
 
* edad
* genero
* nivel educativo de los padres
* asistencia
* horas de estudio
* calificacion final
 
 Cantidad de registros: 12000

 En esta fuente de datos se conserva y maneja informacion sobre un determinado grupo estudiantil, donde se observan claves fundamentales para el entendimiento de las caracteristicas del rendimiento academico de los grupos estudiantiles.
 
## Listado de herramientas utililzadas 

* Python( Pandas,Numpy)
* Google Colab
* Matplotlib, Seaborn , Plotly
* Power BI
* GITHUB
  
  En el proceso de preparacion y limpieza se utilizo herramientas como Python y Pandas, donde luego realizamos un revision para poder asegurar la inocuidad de los datos y poder proseguir con la realizacion de metricas y variables para realizar el analisis de las mismas

  Como resultado obtuvumos un Notebook limpio y estructurado, en formato csv para poder proseguir con la visualizacion en Power BI teniendo en cuenta los graficos que realizamos anteriormente en Google Colab con sus librerias de graficos.
## ¿Como ejecutar el proyecto?

* Clonar Repositorio: 
git clone https://github.com/Lujan18/Analisis_Estudiantiles.git

* Instalar librerias:
pip install pandas numpy matplotlib seaborn plotly

## Resultados Principales:

 Luego de realizar el analisis correspondiente con funciones y graficos, llegamos a la conclusion de que no hay ningun factor común mas allá de las horas de estudio dedicadas por cada estudiante, ya que solo este fator demuestra una leve importancia para el rendimiendo academico. 

 No se vio ninguna relación entre el rendimiento de los estudiantes para con la edad, el género, el nivel de asistencia o nivel educativo de los padres y el rendimiento final, solo cierta correlación con las horas de estudio dedicadas por cada estudiante y sus notas finales.
 
## Visualizacion en Power BI

 Una vez que obtuvimos un archivo limpio y apto, proseguimos con la realización de un dashboard en Power BI
 
 Vista de graficos:
 
<img width="399" height="233" alt="image" src="https://github.com/user-attachments/assets/250bc394-8321-4e96-a07a-20f42601c988" />
<img width="429" height="224" alt="image" src="https://github.com/user-attachments/assets/eca62ba1-dfec-41bd-9536-e7abe0ffcdda" />
<img width="438" height="225" alt="image" src="https://github.com/user-attachments/assets/8e4e563c-f0b1-444a-9491-0f8d6505d2b1" />
<img width="393" height="222" alt="image" src="https://github.com/user-attachments/assets/7186971b-a453-4d0e-a5a2-3d2194570845" />

## ¿Que vimos en estos graficos?

 Explicacion de los graficos adjuntos:

 En estos graficos podemos observar la relacion de distintas variantes para con la calificacion final de los estudiantes, en las mismas no se presenta algun tipo de factor que pueda ser determinante para con el rendimiento de los estudiantes, pero si hemos logrado visualizar en conjunto con el analisis anterior es que las horas de estudio si pueden afectar al resultado final.

## Gráfico 1: Calificacion según asistencia y género

 Se puede observar con total claridad en promedio de calificación de los estudiantes segun el nivel de asistencia y el género de los mismos, los datos demuestran un nivel muy parejo de calificación entre estas variables

## Gráfico 2: Calificación según nivel educativo de los padres
 
 Aqui vemos el promedio de calificacion de los estudiantes segun el nivel educativo de los padres, se muestran una pequeña diferencia segun la educación de los padres de nivel secundario y de posgrado, pero nada a nivel relevante.

## Gráfico 3: Calificación según edad y genero
 
 En este grafico se analiza el promedio de calificacion final según la edad y el género, donde vemos que las mujeres de 16 años mantienen su promedio por arriba del de los hombres pero la situacion cambia al ver que los hombres entre 17 y 18 años mantienen un promedio mas alto, de igual manera no se observan grandes diferencias.
 
## Gráfico 4: Horas de estudio y calificación según asistencia

 En este ultimo grafico vemos el promedio de horas de estudio y el promedio de calificación final según el tipo de asistencia, donde vemos que los estudiantes con un promedio de casi 110 horas mantienen su promedio en 70 puntos, y los estudiantes con un promedio de casi 115 horas de estudio se mantiene el 73 puntos.

## Conclusion

 No se observan factores que afecten al rendimiento académico de los estudiantes, si bien se encontraron algunos puntos de diferencia, el unico que destaco fue el factor de las horas de estudio.
 
## Entonces, que se puede entender con estos datos?

 En este punto podemos determinar que los factores que son determinantes para el rendimiento academico son, casi en su totalidad, factores puramente manejados por los mismos estudiantes, ya que no encontramos factores externos que afecten de alguna manera a su puntuación.

 ## Enlaces 
 - https://github.com/Lujan18/herramientasbasicas-sanchez-micaela/blob/main/data/raw/datos_estudiantes_id_csv [Dataset original (CSV)]
 - https://github.com/Lujan18/herramientasbasicas-sanchez-micaela/blob/main/data/processed/datos_estudiantes_limpio.csv [Dataset limpio(CSV)]

 ## Referencias
 - Pandas development team. (2024). *pandas: powerful Python data analisys toolkit*. http://pandas.pydata.org/docs/
 - Hunter , J. D.(2007). Matplotlib: A 2D graphics environment. *Computing in Science & Engineering* , 9(3), 90-95. http://,atplotlib.org/stable/cite.html
 - Waskom, M. (2021). seaborn: statistical data visualization. *Journal of Open Source Software* , 6(60), 3021. https://seaborn.pydata.org/citing.html
 - Google. *Google Colaboratory*. https://colab.research.google.com/
 - Microsoft. *Power BI documentation*. https://learn.microfoft.com/power-bi/
 - Dataset: Elaboración propia con Python (2026). Sin fuente externa
 - Imágenes: Capturas propias del dashboard en Power BI (2026).

# Autor:
Micaela Sanchez

https://www.utn.edu.ar/es/ [Link de la institucion estudiantil]

https://www.linkedin.com/in/micaela-luj%C3%A1n-sanchez-7bb69a336 [Link del perfil de Linkedin]
