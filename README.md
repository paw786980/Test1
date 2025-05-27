🧪 Prueba Técnica 1:

📋 Descripción
Desarrolla un pequeño servicio backend usando FastAPI o Flask que realice lo siguiente:

Lea un archivo CSV de dataset de clientes al iniciar el servidor.

Exponga los siguientes endpoints REST:

GET /clientes: retorna todos los registros del CSV.

GET /analisis: retorna los siguientes análisis calculados usando Pandas:

Número total de registros.

Promedio de edad.

Total de compras por país.

Promedio de compras por rango de edad:

18-25

26-35

36-50

51+

Empaqueta toda la aplicación en un contenedor Docker listo para correr con docker run.

✅ Requisitos funcionales

Usar la librería Pandas para el análisis de datos.

Exponer los datos como respuesta en formato JSON.

Incluir un Dockerfile funcional.
