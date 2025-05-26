🧪 Prueba Técnica 1 (20 min): Backend Python + Análisis + Docker
📋 Descripción actualizada:
Desarrolla un pequeño backend con FastAPI o Flask, que lea un archivo dataset de clientes y exponga dos endpoints. Además, empaqueta la aplicación en un contenedor Docker listo para correr.

✅ Requisitos:
Endpoint /clientes: retorna todos los registros.

Endpoint /analisis: devuelve:

Número total de registros.

Promedio de edad.

Total de compras por país.

Dockerfile funcional para correr el backend con docker run.

Opcional: usar pandas para análisis.

📂 Dataset de ejemplo:

nombre,edad,pais,compras
Juan,32,México,1200
Ana,27,Colombia,1500
Luis,45,México,950
Laura,30,Chile,1750
