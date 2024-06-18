# Práctica 2 - Visualización de Datos

## Descripción
Este proyecto se centra en la creación de visualizaciones de datos utilizando Tableau para analizar la prevalencia de enfermedades crónicas en Estados Unidos a lo largo del tiempo. Los datos utilizados han sido procesados para obtener insights significativos sobre las tendencias de enfermedades.

## Estructura del Proyecto
- **Tableau**: Contiene los archivos de Tableau con las visualizaciones creadas.
- **datos**: Contiene los archivos CSV utilizados en el proyecto.
- **src**: Contiene el código fuente y scripts utilizados en el procesamiento de datos.

## Cómo Añadir una Nueva Pestaña en el Dashboard de Tableau
1. **Crear una Nueva Hoja**:
   - Haz clic en el icono de hoja con el signo "+" en la parte inferior de la ventana de Tableau para crear una nueva hoja de trabajo.
   - Configura la visualización utilizando los datos que necesites.

2. **Añadir la Nueva Hoja al Dashboard**:
   - Abre el dashboard existente.
   - Haz clic en el icono de dashboard con el signo "+" para crear un nuevo dashboard.
   - Arrastra la nueva hoja desde la lista de hojas a este nuevo dashboard.

3. **Navegación entre Pestañas**:
   - Para permitir la navegación fácil entre diferentes pestañas, añade acciones de navegación. Ve a `Dashboard` > `Actions` y añade una acción de navegación para que los usuarios puedan moverse entre pestañas.

## Ejemplo de Visualización Temporal
Para crear una gráfica de tiempo con los datos disponibles:
1. **Carga de Datos**: Importa el archivo CSV a Tableau.
2. **Configurar Columnas y Filas**:
   - Arrastra `Year Start` a las columnas y `Topic` a las filas.
3. **Medidas**:
   - Arrastra una medida relevante a las filas (por ejemplo, `Count of Records`).
4. **Tipo de Gráfico**:
   - Selecciona el gráfico de líneas para visualizar cómo cambian los valores a lo largo del tiempo.

## Instrucciones para Ejecutar
1. **Importar los Datos**: Abre Tableau y carga los archivos CSV proporcionados en la carpeta `datos`.
2. **Crear Visualizaciones**: Sigue los pasos descritos para crear nuevas hojas y dashboards.
3. **Guardar y Publicar**: Guarda tu trabajo y, si es necesario, publica el dashboard en Tableau Server o Tableau Online.

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
