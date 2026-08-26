# Curso de Data Analytics

Repositorio académico en construcción que reúne los talleres, laboratorios, análisis y entregables desarrollados durante el curso de **Data Analytics**. Su propósito es documentar de manera progresiva el aprendizaje, conservar evidencias reproducibles y mostrar la aplicación de Python y la analítica de datos a diferentes contextos empresariales.

## Información general

| Campo | Información |
|---|---|
| Estudiante | Sara Valentina Guauque Zarrate |
| Asignatura | Data Analytics |
| Código de la asignatura | 43390860 |
| Docente | Ing. Elias Buitrago Bolivar, MSc. |
| Herramientas principales | Python, Google Colab, Jupyter Notebook y GitHub |
| Estado del repositorio | En actualización continua |
| Última actualización | Agosto de 2026 |

## Objetivo del repositorio

Organizar y presentar las actividades del curso como un portafolio académico, mostrando la evolución desde los fundamentos de programación hasta el desarrollo de análisis integrales que incluyen preparación de datos, construcción de indicadores, visualización, estadística, interpretación de resultados y formulación de recomendaciones para la toma de decisiones.

## Entregas realizadas

| N.º | Actividad | Momento | Tema principal | Entregables | Estado |
|---:|---|---|---|---|:---:|
| 1 | [Taller introductorio de Python para Data Analytics](Taller_Introductorio_Pyhon_Data_Analytics.ipynb) | Introducción | Fundamentos de Python, pandas, KPI y visualización | Notebook interactivo | Completado |
| 2 | [Laboratorio 1 – Restaurant Analytics](Lab_1-Semana_2/) | Semana 2 | Integración de datos y análisis comercial de un restaurante | Notebook, bases, informe y README | Completado |
| 3 | [Laboratorio 2 – Accidentalidad laboral](Lab_2-Semana_4/) | Semana 4 | Gestión del riesgo y analítica de Seguridad y Salud en el Trabajo | Notebook, bases, informe ejecutivo y README | Completado |

## Descripción de las actividades

### 1. Taller introductorio de Python para Data Analytics

Actividad individual orientada al aprendizaje de las bases necesarias para trabajar en Google Colab y resolver problemas sencillos de negocio con Python.

**Contenidos desarrollados:**

- Variables, tipos de datos y operaciones aritméticas.
- Cadenas de texto y presentación de indicadores.
- Listas y diccionarios.
- Condiciones y reglas de negocio.
- Ciclos y acumulación de resultados.
- Creación y reutilización de funciones.
- Construcción e inspección de DataFrames con pandas.
- Cálculo de ingresos, costos y margen bruto.
- Agrupación de datos y construcción de KPI por producto.
- Visualización básica con Matplotlib.
- Elaboración de un resumen ejecutivo automático.
- Autoevaluación, seguimiento del progreso y exportación de resultados.

El notebook utiliza un conjunto de datos incorporado, por lo que puede ejecutarse sin descargar archivos adicionales.

### 2. Laboratorio 1 – Restaurant Analytics

Análisis comercial de dos semanas de operación de un restaurante. El laboratorio integra archivos de ventas, productos y clientes para estudiar ingresos, frecuencia de compra y recurrencia.

**Procesos realizados:**

- Reconocimiento de fuentes, llaves y relaciones entre tablas.
- Validación de integridad y consolidación de información.
- Cálculo de ingresos por registro, producto y semana.
- Comparación del desempeño de las dos semanas.
- Identificación de productos con mayor ingreso y frecuencia.
- Medición de la recurrencia de clientes.
- Reproducción de una consulta analítica mediante SQLite.
- Elaboración de gráficos e interpretación ejecutiva.

**Resultados destacados:**

- Se analizaron 250 ventas en cada semana.
- Los ingresos pasaron de **$1.962,68** en la semana 1 a **$1.923,88** en la semana 2, una variación de aproximadamente **−1,98 %**.
- **Steak** fue el producto con mayor ingreso acumulado.
- Se identificaron 46 clientes recurrentes, equivalentes a una tasa de **20,81 %**.
- La recomendación principal fue fortalecer la fidelización y monitorear la recurrencia frente a esta línea base.

### 3. Laboratorio 2 – Accidentalidad laboral

Proyecto de analítica aplicada a la gestión del riesgo y a la Seguridad y Salud en el Trabajo, desarrollado mediante la metodología **CRISP-DM**. Integra información de 3.000 trabajadores, 150 empresas y 1.067 accidentes.

**Procesos realizados:**

- Revisión de calidad, limpieza e integración de tres bases de datos.
- Construcción de una tasa de accidentalidad basada en trabajadores expuestos.
- Análisis por jornada, capacitación, sector económico y sistema de gestión.
- Comparaciones por nivel educativo, cargo, género, edad y antigüedad.
- Cruces entre jornada, sector, cargo y capacitación.
- Identificación de perfiles combinados de mayor riesgo.
- Análisis de lesiones y partes del cuerpo afectadas.
- Aplicación de pruebas chi-cuadrado y cálculo de V de Cramér.
- Elaboración de visualizaciones, conclusiones y recomendaciones preventivas.
- Preparación de un informe ejecutivo de una página para la gerencia.

**Resultados destacados:**

- La tasa general de accidentalidad observada fue de **35,57 %**.
- La jornada nocturna presentó la tasa más alta: **44,96 %**.
- En la noche, minería alcanzó **65,62 %** y construcción **58,09 %**.
- El personal operativo nocturno de minería y construcción conformó los perfiles de mayor riesgo.
- Las empresas sin sistema de gestión presentaron una tasa considerablemente superior a la de aquellas con sistema implementado.
- La relación entre capacitación y accidentalidad se interpretó de forma descriptiva, sin atribuir causalidad.

## Metodologías aplicadas

- Análisis exploratorio de datos.
- Limpieza, transformación e integración de bases.
- Validación de calidad y consistencia de llaves.
- Estadística descriptiva.
- Construcción de indicadores de negocio.
- Comparación mediante frecuencias, porcentajes y tasas con denominador.
- Tablas cruzadas y análisis de perfiles.
- Pruebas de asociación entre variables categóricas.
- Visualización orientada a la comunicación de resultados.
- Metodología CRISP-DM.
- Elaboración de conclusiones y recomendaciones basadas en evidencia.

## Tecnologías y bibliotecas

- **Python:** lenguaje principal de análisis.
- **Google Colab y Jupyter Notebook:** ejecución y documentación del código.
- **pandas y NumPy:** limpieza, transformación, integración y cálculo de indicadores.
- **Matplotlib y Seaborn:** visualización de resultados.
- **SciPy:** pruebas estadísticas.
- **SQLite:** consultas SQL en el Laboratorio 1.
- **Git y GitHub:** control de versiones y publicación del portafolio.
- **Microsoft Word:** elaboración de informes ejecutivos.

## Estructura actual

    curso_Data_Analytics/
    ├── README.md
    ├── Taller_Introductorio_Pyhon_Data_Analytics.ipynb
    ├── Lab_1-Semana_2/
    │   ├── data/
    │   ├── lab1_Sem2_DA_20261.ipynb
    │   ├── Informe lab1.docx
    │   └── README.md
    └── Lab_2-Semana_4/
        ├── Datos/
        ├── lab_Sem4_DA_20262_COMPLETO.ipynb
        ├── Informe_Ejecutivo_Prevencion_Riesgos_CRISP_DM.docx
        └── README.md

Cada laboratorio cuenta con su propio README para explicar con mayor detalle los datos, la metodología, los resultados, las limitaciones y la forma de ejecución.

## Cómo ejecutar los notebooks

### Opción 1: Google Colab

1. Abra el archivo con extensión **.ipynb** desde GitHub.
2. Seleccione la opción **Open in Colab** o cargue el notebook manualmente en Google Colab.
3. Si el laboratorio utiliza archivos externos, cargue también la carpeta de datos correspondiente.
4. Ejecute las celdas en orden mediante **Entorno de ejecución > Ejecutar todas**.
5. Verifique que no existan errores y revise las salidas, tablas y gráficas.

### Opción 2: Entorno local

Se requiere Python 3 y Jupyter Notebook. Las dependencias generales pueden instalarse con:

    pip install jupyter pandas numpy matplotlib seaborn scipy

Después, desde la carpeta del repositorio, ejecute:

    jupyter notebook

SQLite forma parte de la biblioteca estándar de Python y no requiere una instalación independiente en la mayoría de los entornos.

## Principios de trabajo

- Mantener los notebooks ordenados, comentados y ejecutables de principio a fin.
- Conservar las fuentes de datos necesarias dentro de la carpeta de cada laboratorio, cuando su publicación esté autorizada.
- Diferenciar entre conteos absolutos, porcentajes y tasas.
- No presentar asociaciones estadísticas como relaciones causales sin evidencia suficiente.
- Explicar los resultados en lenguaje comprensible para usuarios no técnicos.
- Convertir los hallazgos en recomendaciones concretas, medibles y priorizadas.
- Proteger la información personal y publicar únicamente datos académicos, sintéticos, autorizados o anonimizados.

## Cómo actualizar este README

Cuando se agregue una nueva actividad al repositorio:

1. Crear una carpeta con un nombre uniforme, por ejemplo **Lab_3-Semana_6**.
2. Incluir dentro de ella el notebook, las bases permitidas, el informe y un README específico.
3. Agregar una nueva fila en la tabla **Entregas realizadas**.
4. Crear una subsección en **Descripción de las actividades** con el objetivo, los procesos y los principales resultados.
5. Actualizar la estructura del repositorio, las tecnologías utilizadas y la fecha de actualización.
6. Comprobar los enlaces y ejecutar nuevamente todos los notebooks antes de publicar.

Plantilla para una nueva actividad:

    ### N. Nombre de la actividad

    Breve descripción del problema y del propósito del análisis.

    **Procesos realizados:**

    - Proceso 1.
    - Proceso 2.
    - Proceso 3.

    **Resultados destacados:**

    - Resultado cuantitativo principal.
    - Interpretación más importante.
    - Recomendación propuesta.

## Autoría y colaboración

**Responsable del repositorio:** Sara Valentina Guauque Zarrate.

Los laboratorios han sido desarrollados  con la participación de:

- Shady Alejandra Garay Rodriguez.
- Sergio David Vargas Garzón.



## Alcance académico

Este repositorio fue creado con fines educativos. Los resultados dependen del alcance y la calidad de las bases suministradas en cada actividad y no sustituyen una evaluación profesional o una decisión empresarial basada en información adicional.

No se ha declarado una licencia abierta para la reutilización del contenido. La consulta del repositorio no implica autorización para copiar, redistribuir o presentar los trabajos como propios.
