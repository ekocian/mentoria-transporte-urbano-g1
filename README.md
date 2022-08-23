# mentoria-transporte-urbano-g1
Trabajos practicos mentoria sobre transporte publico de pasajeros Cordoba - Diplodatos 2022

## Integrantes
- Fraire, Juan (juanfraire@gmail.com)
- Kocian, Esteban (egkolo@gmail.com)
- Villagra Torcomian, Ignacio (ignaciovillator@gmail.com)

## [Entregable 1](/entregable_1.ipynb)
### Manipulacion y transformacion de dataset
- Interaccion con bases particionadas
- Conversion de formatos (fecha de string a Datetime)
- Generacion de nuevas variables (mes, día de la semana, hora)

### Aplicacion de estadísticos descriptivos sobre cortes de boleto:
- Calculo de variables espaciales: Corredor, línea y sentido,
- Calculo de Variables temporales: Mes, día de la semana y hora. 
- Analisis de estacionalidad

## [Entregable 2](/entregable_2.ipynb)
### Preprocesamiento del dataset
- Boletos acumulados se resumen en `numtickets.csv`
- Tarjetas indexadas por fechas se guardan en `datescards.csv`
- Intervalos de tiempos se listan en `deltas.csv`

### Posprocesamiento del dataset
- Análisis de boletos acumulados
- Análisis Tarjetas por Fechas

## [Entregable 3](/entregable_3a.ipynb)
### a) Formateo del dataset
- Exploración del dataset
- División de columna FECHA para input de predicción

### b) Filtrado del dataset
- Depuración de datos
- Dataset final para predicción

### c) Predicción
- Uso de Decision Tree Classifier y Random Forest
- Análisis y Evaluación