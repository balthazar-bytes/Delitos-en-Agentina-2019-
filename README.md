Análisis de Delitos en CABA (2019)
Este proyecto consiste en un análisis detallado de los delitos registrados en la Ciudad Autónoma de Buenos Aires (CABA) durante el año 2019. El trabajo integra diversas herramientas de procesamiento y visualización de datos vistas a lo largo del curso.

Contenido del Repositorio
El repositorio incluye los siguientes archivos principales:

delitos.ipynb: Notebook de Jupyter que contiene el código en Python para la carga, limpieza y análisis exploratorio de los datos.

delitos2019.csv: El conjunto de datos fuente en formato CSV con el registro de incidentes.

.gitignore: Archivo para excluir archivos temporales o innecesarios del control de versiones.

Datos Utilizados
El dataset delitos2019.csv cuenta con 117.661 registros y las siguientes columnas clave:

id: Identificador único del delito.

fecha: Fecha en que ocurrió el incidente.

franja_horaria: Hora aproximada del suceso.

tipo_delito: Categoría del delito (Ej: Robo, Hurto, Lesiones).

subtipo_delito: Detalles específicos del tipo de delito.

barrio / comuna: Ubicación geográfica dentro de CABA.

lat / long: Coordenadas geográficas para mapeo.

Hallazgos Principales
A través del análisis en el notebook, se identificaron puntos críticos de criminalidad en la ciudad:

Barrios con Mayor Cantidad de Delitos registrados:
Palermo: 9.559 incidentes.

Balvanera: 9.239 incidentes.

San Nicolás: 6.246 incidentes.

Recoleta: 5.589 incidentes.

Flores: 5.518 incidentes.

Barrios con Menor Cantidad de Delitos registrados:
Puerto Madero: 283 incidentes.

Villa Real: 343 incidentes.

Versalles: 392 incidentes.

Requisitos
Para ejecutar el análisis se requiere:

Python 3.x

Pandas

Jupyter Notebook / Lab

Matplotlib (para visualizaciones)

Instalación y Uso
Clonar el repositorio.

Asegurarse de tener el archivo delitos2019.csv en la misma carpeta que el notebook o ajustar la ruta de carga en el código.

Ejecutar todas las celdas del archivo delitos.ipynb para reproducir el análisis.
