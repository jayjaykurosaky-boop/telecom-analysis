# telecom-analysis
# ConnectaTel – Análisis Exploratorio y Segmentación de Clientes

## Objetivo del proyecto
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre la información de clientes y su consumo de servicios de ConnectaTel. El propósito es identificar problemas de calidad de datos, comprender los patrones de uso, segmentar a los clientes y generar conclusiones accionables que apoyen decisiones de negocio.

## Datasets utilizados
El notebook trabaja con los siguientes conjuntos de datos:
- **users**: información demográfica y del plan contratado por cada cliente.
- **calls**: registros de llamadas realizadas.
- **messages**: registros de mensajes enviados.
- **internet** (o uso de datos): consumo de datos móviles por usuario.

## Etapas del análisis
1. Carga y exploración inicial de los datos.
2. Identificación de problemas de calidad (valores nulos, sentinels, inconsistencias y fechas).
3. Limpieza y estandarización de datos.
4. Generación de estadísticas descriptivas por usuario.
5. Visualización de distribuciones e identificación de valores atípicos.
6. Segmentación de clientes por nivel de uso y por edad.
7. Elaboración de hallazgos y conclusiones ejecutivas con oportunidades de negocio.

## Cómo ejecutar el notebook
### Opción 1: Google Colab
1. Descarga este repositorio o clónalo.
2. Abre Google Colab.
3. Selecciona **Archivo → Subir notebook** y carga `S7 Version-Estudiante-Project-ConnectaTel.ipynb`.
4. Si es necesario, carga los archivos de datos en la sesión de Colab.
5. Ejecuta las celdas en orden, de principio a fin.

### Opción 2: Jupyter Notebook
1. Instala Python 3 y Jupyter.
2. Instala las dependencias utilizadas en el notebook (por ejemplo: pandas, numpy, matplotlib y seaborn).
3. Coloca los datasets en la ruta esperada por el notebook.
4. Ejecuta todas las celdas en orden.

## Guía de reproducción
1. Obtener los datasets del proyecto.
2. Abrir el notebook en Google Colab o Jupyter.
3. Ejecutar todas las celdas siguiendo el orden establecido.
4. Revisar las visualizaciones, estadísticas y segmentaciones generadas.
5. Analizar las conclusiones finales para identificar oportunidades comerciales y de segmentación.
