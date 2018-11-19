# Trabajo Final

### Integrantes
Daniel Morales Londoño   cod: 201510090010

### Descripcion
Este trabajo tiene como objetivo aplicar los conocimientos adquiridos en la asignatura ingeniería del conocimiento.
con la ayuda del docente se ha elegido previamente un dataset al cual se le hará un análisis y se intentará
sacar conclusiones de sus datos a través de algomitmos de machine learnig.
con el fin de evidenciar mejor los resultados se soportará las algoritmos con graficas a traves de matplot


## DataSet
### conjunto de datos de consumo de energía eléctrica de un hogar
el data set elegido corresponde a mediciones del consumo de energía eléctrica en un hogar con una tasa de muestreo
de un minuto durante un período de casi 4 años. contiene los siguentes datos.

### Datos
1.fecha: fecha en formato dd/mm/aaaa cambiado a formato ddmmaaaa
2.hora: hora en formato hh: mm: ss cambiado a formato hhmmss
3.global_active_power: potencia activa promediada en minutos global del hogar (en kilovatios)      (KW-min)
4.global_reactive_power: potencia reactiva promediada en minutos global del hogar (en kilovatios)  (KW-min)
5.voltaje: voltaje promediado en minutos (en voltios)                                              (V-min)
6.intensidad_global: intensidad actual promediada en minutos global (en amperios)                  (A-min)
7.sub_metering_1: submedición de energía No. 1 (en vatios-hora de energía activa ). Corresponde a la cocina, que contiene  principalmente un lavaplatos, un horno y un microondas (las placas eléctricas no son eléctricas sino que funcionan con gas).W-h 
8.sub_metering_2: sub-medición de energía No. 2 (en vatios-hora de energía activa). Corresponde a la lavandería, que contiene una lavadora, una secadora, una nevera y una luz. (W-h)
9.sub_metering_3: sub-medición de energía No. 3 (en vatios-hora de energía activa). Corresponde a un calentador de agua eléctrico y un acondicionador de aire. (W-h)
https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption

### Cambio
El dataset que se utiliza ha sufrudo una serie de cambios las cuales considero se deben mensionar, original mente
el dataSet contie 2075.259 filas pero esta cifra se ha reducido a tan solo 400.000 para facilitar su manejo,
reducir el tiempo de procesamiento de los algoritmos y la persistencia de este proyecto en github 
(no permite archivos mayores a 100MB)


## Algoritmos Utilizados
La expliación del por que se han elegido estos algoritmos está dentro de la implementación de cada uno de estos:
Regresión, Agrupación, Desitional Tree

## Nota
se aconseja visitar el código en el siguiente orden
Regresión, Agrupación, Desitional Tree