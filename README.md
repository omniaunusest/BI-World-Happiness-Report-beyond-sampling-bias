# Data Insights – World Happiness Report: más allá de las muestras


## Auditoría de la Calidad del dato y su metodología

Comprobamos cómo se distribuye y explica la felicidad a nivel mundial entre el segmento 2012-2022, identificando patrones zonales y factores asociados, mediante la conversión de datos complejos en visualizaciones interactivas accesibles.

En este proyecto trabajamos con los datos en bruto del **World Happiness Report** (WHR) como data set principal para analizar y visualizar factores relacionados con el bienestar y la felicidad a nivel global.  

El objetivo es aplicar un flujo completo de **EDA, ETL y visualización**, usando **Python**, **Jupyter Notebooks** y **Power BI**, para hacer un análisis crítico, detectar patrones de manera efectiva y visualizar insights de forma clara.

El proyecto se apoya en los principios metodológicos exploración, limpieza, análisis crítico y visualización, adaptados al enfoque de Business Intelligence.

---

## Objetivos

- Explorar, comprender y contextualizar los datos del *WHR*.

- Preparar y transformar los datos mediante procesos de **EDA y ETL** desarrollados con Python.

- Crear **visualizaciones y dashboards** que faciliten tanto la interpretación de los datos, como preguntarse críticamente al respecto.

- Comunicar hallazgos relevantes de forma visual y estructurada.

- Sentar una base flexible para la incorporación de **datasets adicionales**.

---

## Metodología

- Metodología SCRUM (Agile) para gestión del tiempo de proyecto (2 sprints, 4 semanas).

- **EDA y ETL** con Python y Jupyter Notebook.

- **Limpieza**, **transformación** y **validación** de datos.
- Organización del código con funciones reutilizables en una carpeta `src` en archivos `.py`.
- Visualización de datos mediante:
  - **Power BI**, para visualizaciones interactivas, filtros complejos y personalización de paneles de control.
- Análisis crítico de resultados y comunicación de insights.

---

## Insights WHR, los datos recogidos

La felicidad no se distribuye de forma homogénea entre países ni regiones.

Al analizar la evolución temporal de la felicidad a nivel global, muestra estabilidad relativa, con variaciones a lo largo del tiempo de caracter descendente.

Mensaje clave:
Existe una relación positiva entre PIB y felicidad, pero no es lineal ni suficiente por sí sola.

Los factores sociales explican mejor la felicidad que la riqueza por sí sola.

¿Qué entendemos por “felicidad” según los datos del World Happiness Report?

Conclusiones principales:

- La felicidad no es solo una cuestión económica.
- Los factores sociales tienen un peso clave.
- El contexto regional influye de forma significativa.
- Existen diferentes modelos de bienestar entre países.

Cierre de esta parte del análisis:
La felicidad es un fenómeno multidimensional que combina riqueza, contexto social y disponibilidad de recursos.

## Insights Metolodogía, cómo se han recogido los datos


## Estructura del repositorio

```text
BI-WHR-BEYOND-THE-DATA
│
├── data/
│   └── Raw data y Datos transformados
├── docs/
│   └── Corpus teórico de trabajo y apoyo
├── img/
│   └── Recursos gráficos
├── notebooks/
│   └── EDA, Transformaciones
├── src/
│   └── scripts de apoyo para ETL y análisis
│
├── medoria-documento-tecnico.mc
├── README.md
└── whr-dashboads.pbix
```

## Autoría

Este proyecto ha sido realizado por un equipo de analistas con distintos backgrounds formativos en el entorno educativo de la comunidad de Adalab:

- **Andrea R. Virgós** (@andreavirgos)
- **Claudia Cervantes** (@cloud9international)
- **Mayka Durán** (@Maykaduran)
- **Ona Z. Fernández** (@omniaunusest)
- **Patricia Merchán** (@patrimerchan)

Bootcamp Data Analytics & AI – Adalab 
