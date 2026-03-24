🌦️ Forecast Weather Project (FWP)


Proyecto de Business Intelligence que analiza la relación entre condiciones climáticas en Canadá, ventas y costos logísticos, con el objetivo de identificar los mejores días para realizar envíos y optimizar decisiones comerciales. El sistema integra datos climáticos provenientes de una API meteorológica externa con datos históricos de ventas y transporte, generando KPIs y dashboards interactivos en herramientas BI.

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Objetivo del Proyecto: El objetivo principal del Forecast Weather Project (FWP) es proporcionar una plataforma analítica que permita:
1.Integrar datos meteorológicos de Canadá mediante una API REST.
2.Integrar datos históricos de ventas y costos de transporte desde el ERP.
3.Analizar la correlación entre clima, ventas y logística.
4.Generar KPIs comerciales para apoyar la toma de decisiones.
5.Visualizar los resultados mediante tablas dinámicas y dashboards interactivos.

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🧠 Problema que Resuelve: Las condiciones climáticas pueden afectar significativamente:
1.tiempos de entrega
2.costos de transporte
3.volumen de ventas
Observación: Este proyecto permite identificar patrones climáticos que impactan la operación logística, ayudando a la organización a planificar envíos en condiciones más favorables.

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🏗️ Arquitectura del Proyecto
El sistema funciona como un módulo analítico dentro del ecosistema de Business Intelligence de la organización.

Flujo de datos:
Weather API
     │
     ▼
ETL (Extracción y Transformación)
     │
     ▼
Integración con datos del ERP
     │
     ▼
Modelo de Datos BI
     │
     ▼
Dashboards (QlikView / Power BI)

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚙️ Tecnologías Utilizadas
1.QlikView
2.API REST (Weather API)
3.JSON
4.ETL Scripts
5.Excel / Data Sources

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📦 Funcionalidades Principales

1️⃣ Integración de datos climáticos
* Consumo automático de datos meteorológicos desde una API REST
* Actualización diaria de información.

2️⃣ Integración de datos comerciales
* ventas históricas
* registros de despacho
* costos logísticos
* Los datos son transformados y normalizados para análisis.

3️⃣ Análisis Clima vs Ventas
* tablas pivot
* dashboards interactivos
* KPIs de impacto climático

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Dashboards y Visualización: Los usuarios pueden:
1.filtrar datos por fecha
2.filtrar por región de Canadá
3.analizar tipo de producto
4.exportar resultados a Excel

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

👥 Usuarios del Sistema
Usuario	             Nivel técnico	     Uso
Gerente Comercial	   Medio	             Toma de decisiones estratégicas
Analista Comercial	 Alto	               Exploración de datos y reportes
Administrador BI	   Alto	               Mantenimiento del sistema

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🖥️ Requisitos del Sistema: Hardware mínimo
* CPU: Intel Core i5 2.4 GHz
* RAM: 16 GB
* Almacenamiento: 100 GB SSD
* Windows Server
* Power BI Desktop / QlikView
* Chrome 90+
* Edge 90+

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔐 Requisitos No Funcionales
1.Rendimiento
2.Recarga completa de datos: < 15 minutos
3.Respuesta de dashboards: < 3 segundos
4.Autenticación mediante Active Directory
5.Seguridad a nivel de fila (RLS) para datos sensibles
6.Disponibilidad del sistema: 99.5% durante horario laboral

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📂 Estructura del Proyecto
Forecast-Weather-Project
│
├── data
│   ├── weather
│   └── sales
│
├── etl
│   ├── scripts
│   └── transformations
│
├── dashboards
│   ├── powerbi
│   └── qlikview
│
├── docs
│   └── SRS
│
└── README.md

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚠️ Limitaciones del Proyecto

* genera predicciones meteorológicas
* modifica rutas logísticas
* reemplaza el ERP
* gestiona pagos o facturación

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📚 Documentación: La especificación completa del sistema sigue el estándar: IEEE 830 — Software Requirements Specification (SRS) Incluye:
1.requisitos funcionales
2.requisitos no funcionales
3.casos de uso
4.arquitectura del sistema

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Pasos para correr proyecto:

1.Configurar la API Key en el ETL
2.Verificar que los datos estén en /data/sales/
3.Ejecutar el ETL
4.Abrir el dashboard en QlikView
5.Actualizar los datos
6.Analizar los resultados en los dashboards

//-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

👨‍💻 Autor
Marcos Daniel Rojas Cuervo
Politécnico Internacional – Sede Sur
Proyecto académico de Business Intelligence y Análisis de Datos
