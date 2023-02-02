<p align="center" width="100%">
    <img width="33%" src="https://github.com/JFVJ/Saber-Pro-20_21/blob/main/Im%C3%A1genes/logo-prueba-2022_saber11.png"> 
</p>

Desde el 2009 el Instituto Colombiano para el Fomento de la Educación Superior (ICFES) es una entidad autónoma que está vinculada al Ministerio de Educación Nacional y tiene como objeto entre sus diversas funciones velar por la calidad de la educación de los colombianos a través de organizar e implementar las diferentes pruebas Saber (3,5,7,9 que se aplican a nivel de educación básica, 11  para educación media y Pro para educación superior); diseñar y  la base de datos sociodemográficos y de resultados de los estudiantes que presentan las diferentes pruebas; realizar estudios e investigaciones en el campo de la evaluación de la calidad de la educación que permitan dar recomendaciones sobre políticas públicas. 

Con respecto a las pruebas Saber 11, estas son realizadas 2 veces al año y miden los conocimientos de los estudiantes graduados de bachillerato en 5 áreas académicas (Lectura crítica, Matemáticas, Ciencias Sociales y Ciudadanas, Ciencias Naturales e Inglés pesando cada una 100 puntos para un total de 500), siendo esta prueba uno de los requisitos para iniciar la vida universitaria puesto que el resultado se ha convertido en uno de los criterios para muchas instituciones de educación superior (El top 5 de universidades en Colombia según Times Higer Education para 2022 son Icesi y la Javeriana exigiendo de 250 a 300 puntos para el ingreso sin contar medicina, Los Andes 300 puntos mínimo, la U. Nacional y la de Antioquia teniendo sus propios exámenes pero como requisito haber presentado la prueba). 

Como beneficio de obtener un resultado sobresaliente en esta prueba es posible recibir la beca Andrés Bello, otorgada por el gobierno a los 50 mejores puntajes la cual costea la inversión de los estudios de educación superior, o acceder al crédito condonable Generación E. ofrecido por el Icetex.

Debido a lo anterior es de interés entender los resultados, acotando por disponibilidad de la información completa a 2020 y 2021 (info tomada en oct.2022), los posibles factores de éxito en las pruebas Saber 11 teniendo como objetivos en este caso de estudio lo siguiente:
* Entender el contenido de los archivos de datos obtenidos de https://www2.icfes.gov.co/data-icfes  sobre las pruebas Saber 11.
* Identificar características de las variables de interés y relaciones entre ellas por medio de visualizaciones y estadísticas descriptivas.
* Proponer un modelo de Machine Learning que busque relacionar las variables de interés con el desempeño de los estudiantes.

Para lograr los objetivos propuestos, dividiremos este notebook en 3 fases:

1. **Obtener e inspeccionar archivos.** El objetivo en esta esta fase es extraer, evaluar la completitud e idoneidad de la información contenida e incluir nuevas variables y agrupaciones que consideremos pertinentes para el análisis.

2. **Identificar características y relaciones entre las variables.** El objetivo en esta esta fase es explorar visualmente por medio de librerías gráficas la composición de nuestros datos para obtener algunas estadísticas descriptivas de la población y los resultados a nivel sociodemográfico. 

3. **Abordar relación variables-desempeño a través de un modelo.** El objetivo en esta esta fase es Evaluar a través de modelos de Machine Learning de clasificación,  las variables sociodemográficas que inciden en puntajes sobresalientes (por encima del 70%) y explicar la calidad del modelo obtenido.

Debido a situaciones de compatibilidad de la visualización de las gráficas de mapas coropléticos, te invito a visualizar el notebook en el siguiente [enlace:](https://nbviewer.org/github/JFVJ/Saber_11-20_21-/blob/main/Factores%20de%20%C3%A9xito%20pruebas%20Saber%2011%20%2820-21%29.ipynb)
