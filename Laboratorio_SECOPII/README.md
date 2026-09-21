# Equipo 9 - Expediente D: Contrato que crece

## Abrir primero

Lea **Guia_Avance_y_Sustentacion_Equipo9_D.pdf**. La página 1 identifica el entregable; la 3 explica las tres decisiones; las 4-6 explican E1-E3; la 7 contiene el guion de tres minutos; las 8-9 incluyen 14 preguntas con respuestas; la 11 explica cómo ejecutar; la 12 deja la consulta al profesor.

## Lo que corresponde al primer avance

- **SECOP_Equipo9_Avance1.ipynb**: notebook ejecutado, con 16 celdas de código, resultados y respuestas. El anexo final se identifica expresamente como preparación de semana 2.
- **Tablero_Evidencia_Equipo9_D.docx**: la plantilla original diligenciada con exactamente tres tarjetas y la declaración de uso de IA.
- **data/**: los dos CSV y los dos JSON originales, necesarios para reproducir. No se modificaron.
- **resultados/**: tablas, controles, base analítica reducida y figuras regenerables. Las cifras de las tarjetas provienen de E1, E2 y E3.

El HTML es una vista de lectura del notebook, no un reemplazo de la entrega reproducible. La guía y el inventario son material de apoyo; no son un entregable adicional impuesto por el profesor.

## Advertencia de alcance que debe mantenerse

El brief pide adiciones monetarias; el notebook específico cuenta registros de modificación; el blog analiza días adicionados. Se mantienen las tres definiciones separadas. El archivo auxiliar no ofrece montos estructurados ni cobertura completa de 2024-2025. El valor total registrado no se declara inicial sin verificación. Por eso **la razón presupuestal no se pudo calcular de manera validada con estos archivos**.

E1 y E2 describen **registros localizados en la descarga**. E3 es una **ruta temporal complementaria del blog** y debe confirmarse con el profesor que pueda integrar el tablero del expediente presupuestal. No afirmar que 0,148% sea una tasa real de adiciones ni que 9,486% sea un porcentaje de aumentos de presupuesto.

## Cómo ejecutar en Colab

1. Abra el archivo .ipynb en Colab.
2. Ejecute desde la primera celda. Cuando aparezca el cargador de archivos, suba el ZIP completo que contiene este paquete (o el ZIP original del equipo 9).
3. El cargador extrae solo los dos CSV y los dos metadatos. Ejecute las demás celdas en orden.
4. Compruebe que al final aparezca VERIFICACIONES SUPERADAS. Guarde la copia ejecutada del notebook.

Si ya subió los archivos, ubíquelos dentro de data/. El cargador admite Data/, pero las mayúsculas de las rutas son significativas en algunos sistemas.

## Cómo ejecutar en Jupyter

Descomprima el paquete. Abra el notebook desde la carpeta Equipo9_ExpedienteD, junto a data/. El entorno requiere pandas, numpy, matplotlib e IPython. Las versiones probadas están en requirements.txt y resultados/versiones_y_huellas.json. Ejecute todas las celdas de principio a fin.

No hace falta una conexión a datos.gov.co para calcular las evidencias. El notebook no cambia los filtros ni vuelve a descargar datos. La prueba SHA-256 detendrá la ejecución si se mezclan versiones de CSV.

## Cifras de control

| Control | Resultado |
|---|---:|
| Contratos / columnas originales | 50.000 / 85 |
| Contratos con registro localizado | 74 |
| Eventos emparejados | 76 |
| Cobertura de coincidencia | 0,148% |
| Mediana valor: con registro / sin registro localizado | COP 23.820.000 / COP 18.000.000 |
| Contratos con días adicionados | 4.743 |
| Proporción con días adicionados | 9,486% |
| Mediana de días entre positivos | 57 |

## Antes de entregar

Complete los integrantes y la fecha efectiva. Ejecute y contraste las cifras; registre una verificación humana real y una decisión que el equipo no haya delegado. Los criterios propuestos no son un prerregistro previo a los resultados. Confirme con el docente la medida evaluada y la fecha de entrega.

La declaración de IA distingue las comprobaciones técnicas realizadas en el desarrollo asistido de la revisión del equipo, que no puede afirmarse de antemano.

## Datos personales y bancarios

Los CSV originales incluyen columnas personales y bancarias. No publique este ZIP ni los CSV completos en un repositorio abierto sin revisar esas columnas. Para la sustentación use las figuras y las exportaciones reducidas, no vistas innecesarias de información personal.
