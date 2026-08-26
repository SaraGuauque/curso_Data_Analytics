# Análisis de accidentalidad laboral con CRISP-DM

Proyecto académico de analítica de datos orientado a identificar patrones de accidentalidad laboral y formular recomendaciones preventivas basadas en evidencia. El análisis integra información de trabajadores, empresas y accidentes, con énfasis en jornada, sector económico, nivel educativo, cargo, género, antigüedad, capacitación y sistema de gestión.

## Información académica

- **Asignatura:** Data Analytics
- **Código:** 43390860
- **Actividad:** Laboratorio aplicado de analítica empresarial n.º 2 – Semana 4
- **Tema:** Gestión del riesgo y Seguridad y Salud en el Trabajo (SST)
- **Metodología:** CRISP-DM
- **Docente:** Ing. Elias Buitrago Bolivar, MSc.

## Integrantes

- Sara Valentina Guauque Zarrate
- Shady Alejandra Garay Rodriguez
- Sergio David Vargas Garzón

## Objetivo

Analizar la accidentalidad laboral de la población estudiada, reconocer los grupos y contextos con mayor exposición y proponer acciones de intervención priorizadas para apoyar la toma de decisiones en SST.

## Contenido del repositorio

- **lab_Sem4_DA_20262_COMPLETO.ipynb:** notebook completo, documentado y ejecutado, con preparación de datos, análisis estadístico, tablas, visualizaciones, conclusiones y recomendaciones.
- **Informe_Ejecutivo_Prevencion_Riesgos_CRISP_DM.docx:** informe ejecutivo de una página con los resultados más relevantes y las recomendaciones de intervención.
- **datos/trabajadores.csv:** características demográficas y laborales de 3.000 trabajadores.
- **datos/empresas.csv:** información de 150 empresas.
- **datos/accidentes.csv:** registros de 1.067 accidentes laborales.

Estructura sugerida:

    proyecto-accidentalidad/
    ├── README.md
    ├── lab_Sem4_DA_20262_COMPLETO.ipynb
    ├── Informe_Ejecutivo_Prevencion_Riesgos_CRISP_DM.docx
    └── datos/
        ├── trabajadores.csv
        ├── empresas.csv
        └── accidentes.csv

## Metodología

El trabajo sigue las etapas de CRISP-DM:

1. **Comprensión del negocio:** definición del problema de accidentalidad y de las necesidades de prevención.
2. **Comprensión de los datos:** revisión de estructura, calidad, valores faltantes, duplicados y consistencia de llaves.
3. **Preparación de los datos:** limpieza, homologación de variables e integración de las tres bases.
4. **Modelado analítico:** cálculo de indicadores, tablas cruzadas, perfiles combinados y pruebas de asociación.
5. **Evaluación:** interpretación de los resultados, revisión de limitaciones y priorización de hallazgos.
6. **Despliegue:** presentación de gráficos, conclusiones, recomendaciones y regla de priorización preventiva.

## Indicador principal

La tasa de accidentalidad se calculó así:

    Tasa de accidentalidad (%) =
    trabajadores con al menos un accidente / trabajadores expuestos × 100

Esta definición evita contar varias veces a una persona que haya presentado más de un accidente. Los conteos de eventos se muestran por separado cuando son pertinentes.

## Análisis incluidos

El notebook contiene, entre otros, los siguientes análisis:

- Accidentalidad por jornada laboral y capacitación.
- Accidentalidad nocturna por nivel educativo y sector económico.
- Comparación por cargo, género, edad, antigüedad y número de hijos.
- Cruces entre jornada, sector, cargo, capacitación y sistema de gestión.
- Análisis por tipo de empresa y por empresa individual.
- Perfiles combinados de mayor riesgo.
- Lesiones y partes del cuerpo afectadas por jornada y cargo.
- Pruebas chi-cuadrado y medida de asociación V de Cramér.
- Conclusiones ejecutivas y recomendaciones priorizadas.

## Principales resultados

- La tasa general observada fue de **35,57 %**.
- La **jornada nocturna** presentó la tasa más alta: **44,96 %** (308 de 685 trabajadores), aunque la jornada diurna acumuló más casos en términos absolutos.
- En la noche, **minería** alcanzó **65,62 %** y **construcción** **58,09 %**.
- El nivel **técnico** concentró la mayor tasa nocturna entre los niveles educativos analizados: **48,16 %**.
- Las empresas sin sistema de gestión registraron **57,62 %**, frente a **31,10 %** en empresas con sistema implementado.
- Los cargos operativos presentaron **37,64 %** y concentraron 862 casos.
- El grupo de 18 a 24 años presentó **47,34 %**.
- Los perfiles combinados más críticos fueron el personal operativo nocturno de minería (**63,27 %**) y de construcción (**61,61 %**).
- La capacitación registrada no evidenció por sí sola una reducción de la accidentalidad: **41,67 %** en capacitados frente a **31,03 %** en no capacitados. Este resultado es descriptivo y no demuestra que la capacitación cause más accidentes; puede reflejar focalización en grupos de mayor riesgo, diferencias de exposición o necesidad de mejorar su oportunidad, calidad y seguimiento.

## Recomendaciones principales

- Priorizar controles de ingeniería, supervisión y pausas programadas en minería y construcción durante la jornada nocturna.
- Intervenir primero a los perfiles operativos nocturnos y a los trabajadores jóvenes o con menor experiencia.
- Fortalecer los sistemas de gestión en las empresas que no los tienen implementados y auditar su efectividad real.
- Rediseñar la capacitación con contenidos específicos por tarea, evaluación práctica, refuerzos periódicos y seguimiento de indicadores antes y después.
- Implementar acciones sobre los mecanismos que producen fracturas y lesiones de manos, incluyendo barreras físicas, procedimientos seguros y elementos de protección adecuados.
- Usar tasas con denominador, además de conteos, para evitar decisiones sesgadas por el tamaño de los grupos.
- Monitorear mensualmente la accidentalidad por jornada, sector, cargo, empresa y estado de capacitación mediante un tablero de control.

## Cómo ejecutar el notebook

### En Google Colab

1. Abra **lab_Sem4_DA_20262_COMPLETO.ipynb** en Google Colab.
2. Cargue los tres archivos CSV en la sesión o conserve la carpeta **datos** junto al notebook.
3. Verifique que los nombres sean exactamente **trabajadores.csv**, **empresas.csv** y **accidentes.csv**.
4. Seleccione **Entorno de ejecución > Ejecutar todas**.

El notebook busca automáticamente las bases en la carpeta actual, en **/content** y en **datos**.

### En un entorno local

Se requiere Python 3, Jupyter Notebook y las siguientes bibliotecas:

    pip install pandas numpy matplotlib seaborn scipy jupyter

Luego, desde la carpeta del proyecto:

    jupyter notebook

Abra el notebook y ejecute todas las celdas en orden.

## Alcance y limitaciones

Los resultados describen las bases suministradas para el laboratorio. Las asociaciones encontradas no deben interpretarse automáticamente como relaciones causales. Para decisiones empresariales reales se recomienda complementar el análisis con horas trabajadas, nivel de exposición, gravedad, ausentismo, fecha de capacitación, contenido impartido, reincidencia y costos de los accidentes.

## Uso

Proyecto desarrollado con fines académicos. No se ha definido una licencia de reutilización; cualquier uso adicional debe respetar la autoría del equipo y las condiciones aplicables a los datos.
