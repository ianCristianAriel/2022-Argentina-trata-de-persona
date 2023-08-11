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

- **Optimización de Vigilancia Vial en Madrid:** Utilizando datos geoespaciales detallados y de accidentes, se identifican zonas críticas para una mayor vigilancia. Se eligen ubicaciones estratégicas para cámaras, maximizando la cobertura en áreas de alto riesgo y reduciendo accidentes.

- **Selección Inteligente de Ubicaciones para Cámaras Nocturnas:** Se analizan datos de accidentes y existencia de cámaras, identificando momentos de alta incidencia de incidentes. Se determinan calles y áreas para cámaras nocturnas, mejorando la vigilancia durante horas críticas y aumentando la seguridad vial.

- **Decisión Inteligente de Ubicaciones para Cámaras basada en Datos de Calles y Barrios:** Se emplean datos de calles, tráfico y accidentes para tomar decisiones informadas sobre ubicaciones de cámaras. Considerando densidad de tráfico e incidentes en distintos barrios, se optimiza la prevención de accidentes en la ciudad.

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
