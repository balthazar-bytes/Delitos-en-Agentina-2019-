# Análisis de Delitos en CABA (2019)

Este proyecto explora los delitos registrados en la Ciudad Autónoma de Buenos Aires durante el año 2019, utilizando herramientas de procesamiento y visualización de datos.

## Contenido del Repositorio

- **delitos.ipynb**: Notebook de Jupyter con código Python para carga, limpieza y análisis exploratorio de los datos.
- **delitos2019.csv**: Dataset fuente en formato CSV con el registro de incidentes.
- **.gitignore**: Archivo para excluir archivos temporales o innecesarios del control de versiones.

## Descripción de los Datos

El archivo `delitos2019.csv` contiene 117.661 registros con las siguientes columnas principales:

- `id`: Identificador único del delito.
- `fecha`: Fecha del incidente.
- `franja_horaria`: Hora aproximada del suceso.
- `tipo_delito`: Categoría del delito (Ej: Robo, Hurto, Lesiones).
- `subtipo_delito`: Detalles específicos del tipo de delito.
- `barrio` / `comuna`: Ubicación geográfica dentro de CABA.
- `lat` / `long`: Coordenadas geográficas.

## Hallazgos Destacados

El análisis permitió identificar zonas críticas y áreas con menor incidencia:

**Barrios con mayor cantidad de delitos:**
- Palermo: 9.559 incidentes
- Balvanera: 9.239 incidentes
- San Nicolás: 6.246 incidentes
- Recoleta: 5.589 incidentes
- Flores: 5.518 incidentes

**Barrios con menor cantidad de delitos:**
- Puerto Madero: 283 incidentes
- Villa Real: 343 incidentes
- Versalles: 392 incidentes

## Requisitos

- Python 3.x
- Pandas
- Jupyter Notebook / Lab
- Matplotlib

## Instalación y Uso

1. Clona el repositorio.
2. Verifica que el archivo `delitos2019.csv` esté en la misma carpeta que el notebook o ajusta la ruta en el código.
3. Ejecuta todas las celdas de `delitos.ipynb` para reproducir el análisis.

---

Para dudas o sugerencias, puedes abrir un issue en el repositorio.
