# EstadCarla
Grupo: 2

Estudiante: Carla Mendoza

Tema de trabajo:
Causas de las diferencias de la tasa de contagios de COVID-19 durante los primeros 30 días entre distintos países 

Pregunta de investigación:
¿Qué factores explican la diferencia entre la cantidad de contagios por cada 100 mil habitantes durante los primeros 30 días entre distintos países?

Variable dependiente: cantidad de contagios durante los primeros 30 días entre distintos países
- Base de datos: Contagios al mes
     - Variable: Valor
     - Tipo de variable: numérica
     - Fuente: Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University
     - Año de información: 2020
     - Justificación de la variable: Nuestro objetivo general es identificar sus causas



Variables independientes a analizar en esta parte del entregable

Medidas preventivas (tiempo)

Campañas informativas del covid: Evidencia la preocupación de cada país por difundir información sobre la pandemia
 
   - Base de datos: Campañas informativas afterweek
     - Variable independiente: infoalawk
     - Tipo de variable: ordinal
     - Fuente: Banco Mundial
     - Año de información: 2020
     - Justificación de la variable
          Esta información permitirá determinar si, efectivamente, las campañas de información sobre la enfermedad ayudaron a mermar los contagios en el primer mes, si dio igual o si, por el contrario, los incitaron a aumentar.
 
 
Población

Urbanización
 
  i.Población Urbana: Evidencia el porcentaje de la población urbana de un país
  
    - Base de datos: Porcentajes de población Urbana
      - Variable independiente: %poburb18
      - Tipo de variable: numérica
      - Fuente: Banco Mundial
      - Año de información: 2018
      - Justificación de la variable
          Esta información permitirá determinar si el hecho de que un país esté más urbanizado tiene relación con que tenga mayor cantidad de contagiados en el      primer mes o no.
 
  ii.Población Rural: Evidencia el porcentaje de la población rural de un país
  
  - Base de datos: Porcentajes de población Rural
      - Variable independiente: %pobrur18
      - Tipo de variable: numérica
      - Fuente: Banco Mundial
      - Año de información: 2018
      - Justificación de la variable
          Esta información permitirá determinar si el porcentaje de ruralidad que un país posea tiene relación con que tenga mayor cantidad de contagiados en el primer mes o no.
  
  
Capacidad Estatal

Índice de Desarrollo Humano (Human Development Index): Indicador que integra las variables PBI, Educación y Esperanza de vida
  
  - Base de datos: IDH
      - Variable independiente: HDI
      - Tipo de variable: numérica
      - Fuente: United Nations Development
      - Año de información: 2018
      - Justificación de la variable
          Esta información permitirá determinar si el hecho de que un país tenga un mayor IDH estaría relacionado con la cantidad de contagiados que tuvo durante el primer mes o no.


 
###READMEEE###

Todo lo que está en este repositorio ("EstadCarla") es data "limpia". 

El trabajo de limpieza puede encontrarse en el archivo "Ordenamiento de tablas.Rmd".

Para ver las bases originales, puedes ir al repositorio "Prueba".

Medidas preventivas (tiempo)

Campañas informativas del covid
 
    REVISA: public-campaigns-covid.csv
    
Población

Urbanización
 
  i.Población Urbana
  
    REVISA: API_SP.URB.TOTL.IN.ZS_DS2_es_csv_v2_1347951.csv
    
 ii.Población Rural
 
    REVISA: API_SP.RUR.TOTL.ZS_DS2_es_csv_v2_1352737.csv

Capacidad Estatal

Índice de Desarrollo Humano (Human Development Index)
 
    REVISA: IDH.xlsx
    
ASIMISMO, el json es un archivo "colado". Es decir, no aporta a la investigación y solo está en este proyecto como parte de una prueba anterior. Por favor, solo omitir.

