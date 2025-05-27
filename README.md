🧪 Prueba Técnica 1:

📋 Descripción
Desarrolla un pequeño servicio backend usando FastAPI o Flask que realice lo siguiente:

Lea un archivo CSV de dataset de clientes al iniciar el servidor.

Exponga los siguientes endpoints REST:

-GET /clientes: retorna todos los registros del CSV.

-GET /analisis: retorna los siguientes análisis calculados usando Pandas:

-GET /clientes?pais=Nombre: filtra por país.

-GET /clientes/top: muestra el top 3 de clientes con más compras.


✅ Requisitos funcionales

Usar la librería Pandas para el análisis de datos.

Exponer los datos como respuesta en formato JSON.
