🌦️ Forecast Weather Project (FWP)

Proyecto de Business Intelligence que analiza la relación entre condiciones climáticas en Canadá, ventas y costos logísticos, con el objetivo de identificar los mejores días para realizar envíos y optimizar decisiones comerciales.

El sistema integra datos climáticos provenientes de una API meteorológica externa con datos históricos de ventas y transporte, generando KPIs y dashboards interactivos en herramientas BI.

📊 Objetivo del Proyecto

El objetivo principal del Forecast Weather Project (FWP) es proporcionar una plataforma analítica que permita:

Integrar datos meteorológicos de Canadá mediante una API REST.

Integrar datos históricos de ventas y costos de transporte desde el ERP.

Analizar la correlación entre clima, ventas y logística.

Generar KPIs comerciales para apoyar la toma de decisiones.

Visualizar los resultados mediante tablas dinámicas y dashboards interactivos.

🧠 Problema que Resuelve

Las condiciones climáticas pueden afectar significativamente:

tiempos de entrega

costos de transporte

volumen de ventas

Este proyecto permite identificar patrones climáticos que impactan la operación logística, ayudando a la organización a planificar envíos en condiciones más favorables.

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
⚙️ Tecnologías Utilizadas

Power BI

QlikView

API REST (Weather API)

JSON

ETL Scripts

Excel / Data Sources

Windows Server

📦 Funcionalidades Principales
1️⃣ Integración de datos climáticos

Consumo automático de datos meteorológicos desde una API REST

Variables analizadas:

temperatura

precipitación

nieve

Actualización diaria de información.

2️⃣ Integración de datos comerciales

El sistema extrae desde el ERP:

ventas históricas

registros de despacho

costos logísticos

Los datos son transformados y normalizados para análisis.

3️⃣ Análisis Clima vs Ventas

El sistema genera:

tablas pivot

dashboards interactivos

KPIs de impacto climático

Ejemplos de métricas:

ventas promedio vs temperatura

impacto de tormentas de nieve en logística

sobrecosto de transporte por clima adverso

📊 Dashboards y Visualización

Los usuarios pueden:

filtrar datos por fecha

filtrar por región de Canadá

analizar tipo de producto

exportar resultados a Excel

Tipos de visualizaciones:

tablas dinámicas

gráficos de tendencia

análisis comparativos

👥 Usuarios del Sistema
Usuario	Nivel técnico	Uso
Gerente Comercial	Medio	Toma de decisiones estratégicas
Analista Comercial	Alto	Exploración de datos y reportes
Administrador BI	Alto	Mantenimiento del sistema
🖥️ Requisitos del Sistema
Hardware mínimo

CPU: Intel Core i5 2.4 GHz

RAM: 16 GB

Almacenamiento: 100 GB SSD

Software

Windows Server

Power BI Desktop / QlikView

Navegadores compatibles:

Chrome 90+

Edge 90+

🔐 Requisitos No Funcionales
Rendimiento

Recarga completa de datos: < 15 minutos

Respuesta de dashboards: < 3 segundos

Seguridad

Autenticación mediante Active Directory

Seguridad a nivel de fila (RLS) para datos sensibles

Disponibilidad

Disponibilidad del sistema: 99.5% durante horario laboral

📂 Estructura del Proyecto (ejemplo)
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
📈 KPIs Analizados

Algunos indicadores clave:

Ventas promedio por condición climática

Costos logísticos promedio por región

Impacto de tormentas en despachos

Variación de ventas por temperatura

⚠️ Limitaciones del Proyecto

Este sistema NO:

genera predicciones meteorológicas

modifica rutas logísticas

reemplaza el ERP

gestiona pagos o facturación

📚 Documentación

La especificación completa del sistema sigue el estándar:

IEEE 830 — Software Requirements Specification (SRS)

Incluye:

requisitos funcionales

requisitos no funcionales

casos de uso

arquitectura del sistema

👨‍💻 Autor

Marcos Daniel Rojas Cuervo

Politécnico Internacional – Sede Sur
Proyecto académico de Business Intelligence y Análisis de Datos

Si quieres, también puedo ayudarte a hacer una versión aún más profesional para GitHub con:

badges (lenguajes, herramientas, licencia)

imágenes del dashboard

diagramas de arquitectura

GIFs del proyecto

que hacen que tu GitHub se vea mucho más profesional para portafolio.
