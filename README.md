Proyecto: Análisis Comparativo de Tiendas - Alura Store LATAM

📌 Propósito del Análisis

Este proyecto tiene como objetivo evaluar el desempeño de las cuatro tiendas de la cadena Alura Store LATAM mediante el análisis de datos de ventas, productos, calificaciones de clientes, logística y geolocalización. El resultado de este análisis permite recomendar estratégicamente la venta de una de las tiendas menos eficientes, optimizando así los recursos comerciales y operativos.

📁 Estructura del Proyecto

AluraStore/
├── AluraStoreLatam.ipynb           # Cuaderno de análisis completo en Colab
├── Informe_Comparativo_Tiendas.docx # Informe final generado en Word
├── /data/                           # Carpeta opcional para los CSV descargados
├── /figures/                        # Carpeta con los gráficos generados
│   ├── ingresos_totales_tienda.png
│   ├── distribucion_porcentual_ventas.png
│   ├── productos_mas_vendidos_por_tienda.png
│   ├── productos_menos_vendidos_por_tienda.png
│   ├── promedio_calificacion.png
│   └── mapa_calor_ventas.png
└── README.md                        # Este archivo de documentación

📊 Ejemplos de Visualizaciones e Insights

Ingresos Totales por Tienda:


Tienda 4 tiene el ingreso más bajo de toda la cadena.

Distribución Porcentual de Ventas:


Se aprecia una participación porcentual menor de Tienda 4.

Productos más vendidos por tienda:


Tienda 1 lidera en ventas de productos clave.

Promedio de Calificaciones:


No hay diferencias significativas entre tiendas.

Mapa de Calor de Ventas Geolocalizadas:


Las zonas de alta densidad de ventas están dominadas por Tienda 3.

▶️ Instrucciones para Ejecutar el Proyecto

Abre el archivo AluraStoreLatam.ipynb en Google Colab.

Ejecuta las celdas que:

Cargan los archivos CSV desde GitHub.

Limpian y transforman los datos.

Generan los gráficos de análisis.

Evalúan métricas clave: ingresos, calificaciones, costos de envío.

Observa las visualizaciones generadas para obtener insights.

Consulta el archivo Informe_Comparativo_Tiendas.docx para ver la recomendación final.

🧠 Herramientas Utilizadas

Python

Pandas

Matplotlib / Seaborn

Folium (para análisis geoespacial)

Google Colab

Jupyter Notebook

✍️ Autor

[Nombre del analista o equipo de trabajo]Unidad de Análisis Comercial - Alura Store LATAM