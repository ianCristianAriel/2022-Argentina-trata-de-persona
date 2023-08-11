# Prevención de accidentes automovilisticos 

## Descripción

El proyecto se enfoca en el análisis de dos conjuntos de datos relacionados con la ciudad de Madrid. El primero comprende registros de accidentes automovilísticos, mientras que el segundo abarca información sobre las cámaras ubicadas en la ciudad. El objetivo principal de esta investigación es derivar medidas preventivas efectivas con el propósito de reducir significativamente el índice de accidentes en la localidad.

### Estado del proyecto:
**En proceso**

### Estructura de directorios y archivos resultantes

    Proyecto finalizacion - G3
        ├── datos
        │   ├── procesados      <-CSV proesados.
        │   └── brutos           <- CSV originales.
        │
        ├── notebooks          <- Notebooks fraccionados por etapa del proyecto.
        |
        ├── .gitignore         <- Arhivos para ignorar por `git`.
        │
        ├── requerimientos.txt    <- Paquetes y dependencias.
        │
        └── README.md          <- Detalles por escrito.

### Funciones y aplicaciones:

- **Optimización de Cobertura mediante Análisis Geoespacial:** Utilizando datos geoespaciales detallados y la información sobre accidentes automovilísticos, esta funcionalidad tiene como objetivo identificar las zonas geográficas críticas en la ciudad de Madrid que requieren una vigilancia intensificada. Mediante análisis avanzados, se determinarán las ubicaciones estratégicas para la instalación de cámaras de seguridad, maximizando así la cobertura en áreas de alto riesgo y contribuyendo a la reducción de accidentes viales.

- **Selección de Ubicaciones para Cámaras Nocturnas basada en Patrones de Horarios:** Aprovechando los datos de horas de accidentes y combinándolos con información sobre la cantidad de cámaras existentes, esta funcionalidad se centrará en identificar los momentos del día con mayor incidencia de incidentes. Con este análisis, se determinarán las calles y áreas de la ciudad donde la instalación de cámaras con visión nocturna resulta esencial para mantener una vigilancia efectiva durante las horas críticas, contribuyendo a una mayor seguridad vial en todo momento.

- **Decisión Inteligente de Ubicaciones para Cámaras basada en Datos de Calles y Barrios:** Esta funcionalidad aprovechará datos sobre las características de las calles, patrones de tráfico y distribución de accidentes para tomar decisiones informadas sobre la ubicación de las cámaras. Al considerar la intersección de factores como la densidad de tráfico y la frecuencia de incidentes en distintos barrios, se determinarán las ubicaciones óptimas para la instalación de cámaras de seguridad, optimizando la vigilancia y la prevención de accidentes en lugares estratégicos de la ciudad.

### Tecnologías utilizadas:
- Python
  - Numpy
  - Pandas
  - Seaborn
  - Matplotlib
  - Sklearn
  
#### Instalacion de paquetes`

`pip3 install requerimientos.txt`

### Personas Desarrolladoras del Proyecto:
- [@IanCristianAriel](https://github.com/ianCristianAriel)

### Fuente de los datos
- [Dataset de accidentes: madrid.es](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=7c2843010d9c3610VgnVCM2000001f4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default)
- [Dataset de camaras: madrid.es](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=cb7005dc5b2f0710VgnVCM2000001f4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default)

### Licencia
Creative Commons
