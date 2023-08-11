# Análisis de Accidentes de Tráfico y Distribución de Cámaras de Seguridad en Madrid

## Contexto
Ante la actual situación económica y de seguridad en mi país, y con dudas sobre la capacidad de los políticos para mejorarla en los próximos 10 años, decidí explorar cómo podrían ser los índices de accidentes en las principales ciudades de España. Con el objetivo de evaluar la proactividad en seguridad vial, realicé un análisis detallado de Madrid y sus distritos. Utilicé datos del [Ayuntamiento de Madrid](https://datos.madrid.es/), procesados y analizados con Python, y presenté visualizaciones en Tableau.

## Resumen
![Distribución Geográfica de Cámaras](./datos/imagenes%20informe/camaras_distribucion_geografica.png)
Sorprendentemente, Madrid cuenta con un número reducido de cámaras de seguridad registradas. Además, la cantidad de accidentes se correlaciona con la densidad poblacional.

## Puntos de Interés
![Accidentes por Distritos](./datos/imagenes%20informe/accidentes_distritos.png) ![Cámaras por Distritos](./datos/imagenes%20informe/camaras_distrito.png)
Se observa que los distritos con mayor cantidad de accidentes no coinciden necesariamente con aquellos que tienen más cámaras de seguridad.

En esta sección, se muestra cómo la distribución de cámaras se adecua a los diferentes tipos de vías, según los índices de accidentabilidad registrados.

## Conclusiones
![Dashboard de Accidentes](./datos/imagenes%20informe/accidentes_madrid.png)
![Dashboard de Cámaras](./datos/imagenes%20informe/camaras_madrid.png)
Se concluye que Madrid no ha implementado de manera eficiente la distribución de cámaras en relación a los índices de accidentabilidad en los distritos, aunque sí lo ha hecho en función de los tipos de vías.

## Recomendaciones
Se sugiere una mayor instalación de cámaras en las calles de los distritos de Tetuán, el centro de Madrid, San Blas-Canillejas, Moncloa-Aravaca y Chamartín, que presentan las tasas más altas de accidentabilidad.

A nivel general, es necesario revisar las cámaras en las calles y avenidas con capacidad de visión nocturna, dado que la mayoría de los accidentes ocurren en momentos de poca luz.
