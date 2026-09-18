# 📊 Juan David Guerrero — Portafolio de Analista de Datos Junior

<div align="center">

### SQL · Power BI · Tableau · Excel · Python

**Transformando datos financieros, comerciales, de marketing y operativos en hallazgos claros y recomendaciones accionables.**

[LinkedIn](https://www.linkedin.com/in/juan-david-guerrero-parada/) · [GitHub](https://github.com/juandguerrero) · [Correo electrónico](mailto:juangrp12@gmail.com)

</div>

---

## 👋 Sobre mí

Soy **Analista de Datos Junior**, profesional en Administración de Empresas y cuento con más de tres años de experiencia trabajando con información contable, financiera y operativa.

Utilizo **SQL, Power BI, Tableau, Excel y Python** para limpiar y validar datos, definir KPI, identificar tendencias, crear dashboards y traducir los hallazgos en recomendaciones prácticas para el negocio.

Mi experiencia profesional en contabilidad y administración de propiedades me brinda una base sólida en **precisión de datos, conciliaciones, control de procesos y atención al detalle**. Los proyectos que aparecen a continuación demuestran cómo aplico estas fortalezas a preguntas de negocio relacionadas con ventas, clientes, operaciones y marketing.

> 🎯 **Actualmente busco oportunidades como:** Analista de Datos Junior, Analista de BI, Analista de Datos Financieros, Analista de Operaciones y Analista de Operaciones de Ingresos.

---

## 🔎 Lo que hago

**Pregunta de negocio → Limpieza de datos → Validación de datos → Análisis → Visualización → Hallazgos → Recomendaciones**

- Exploro conjuntos de datos para identificar tendencias, patrones y brechas de rendimiento.
- Escribo consultas SQL utilizando joins, CTE, subconsultas y funciones de ventana.
- Construyo modelos de datos y dashboards interactivos en Power BI y Tableau.
- Defino y monitoreo KPI de ventas, ingresos, clientes, marketing y operaciones.
- Valido totales e investigo registros faltantes, duplicados o inconsistentes.
- Comunico los hallazgos utilizando un lenguaje de negocio claro para partes interesadas no técnicas.

---

## 📂 Proyectos destacados

| Proyecto | Pregunta de negocio | Herramientas | Resultado destacado |
|:---|:---|:---|:---|
| [**Análisis del Marketplace de Olist**](https://github.com/juandguerrero/Olist-Marketplace-Sales-Logistics-Analytics/blob/main/README.md) | ¿Cómo evolucionan los ingresos, pedidos, categorías de productos y el desempeño de las entregas? | SQL Server, Power BI, Excel | Analicé **R$13.22 millones** en ingresos por productos e identifiqué una tasa de entregas tardías del **8.11%**. |
| [**Análisis de Ventas de AdventureWorks**](https://github.com/juandguerrero/AdventureWorks-Sales-Analytics-Platform/blob/main/README.md) | ¿Qué productos, clientes, territorios y vendedores impulsan el desempeño? | SQL, Power BI, Python | Descubrí que las bicicletas generaron el **87.7% de los ingresos** y segmenté a los clientes mediante RFM. |
| [**Análisis de Marketing de LearnLoop**](https://github.com/juandguerrero/LearnLoop-Marketing-Analytics-Platform/blob/main/README.md) | ¿La inversión en marketing está generando clientes e ingresos de manera eficiente? | SQL, Tableau, Snowflake, dbt, Python | Conecté **740 mil sesiones** con **9,592 clientes** y calculé un **ROAS de 0.34x**. |

> Estos son proyectos independientes de portafolio desarrollados para demostrar mi flujo de trabajo analítico de principio a fin. Cada repositorio incluye el contexto de negocio, la metodología, el análisis, los dashboards, los hallazgos y las recomendaciones.

---

## 🛒 Análisis del Marketplace de Olist

### Desempeño de ventas, ingresos y entregas

**SQL Server · Power BI · Excel · Modelado de datos · Validación de datos**

#### Problema de negocio

Olist necesitaba una visión consolidada del desempeño del marketplace en pedidos, productos, clientes, vendedores, pagos y entregas. Transformé datos transaccionales fragmentados en un modelo analítico y dashboards para monitorear KPI comerciales y operativos.

#### Lo que hice

- Limpié, relacioné y validé datos provenientes de múltiples tablas relacionales.
- Construí un esquema estrella con una tabla de hechos de ventas y sus respectivas dimensiones.
- Concilié los totales de ingresos y verifiqué duplicados e integridad referencial.
- Creé dashboards en Power BI para analizar ingresos, pedidos, categorías, geografía y logística.
- Convertí los resultados en recomendaciones para la expansión de mercado y la mejora de las entregas.

#### Hallazgos principales

| KPI / Hallazgo | Resultado |
|:---|---:|
| Ingresos por productos | **R$13.22 millones** |
| Pedidos entregados | **96,478** |
| Valor promedio por pedido | **R$137.04** |
| Categoría líder | **Salud y belleza — R$1.23 millones** |
| Participación de São Paulo en los ingresos | **38.3%** |
| Tiempo promedio de entrega | **12 días** |
| Entregas tardías | **8.11%** |

<div align="center">

<img src="dashboards_olist/Dashboards.jpg" alt="Dashboard de Olist Marketplace en Power BI" width="900">

[**Ver proyecto completo →**](https://github.com/juandguerrero/Olist-Marketplace-Sales-Logistics-Analytics/blob/main/README.md)

</div>

---

## 🚲 Análisis de Ventas de AdventureWorks

### Análisis de ventas, clientes, productos y territorios

**SQL · Power BI · Python · Databricks · PySpark · AWS S3 · Airflow**

#### Problema de negocio

AdventureWorks necesitaba una solución unificada de reportes para comprender el desempeño de las ventas e identificar los productos, territorios, clientes y vendedores que más contribuían a los ingresos.

#### Lo que hice

- Preparé y transformé los datos de ventas utilizando SQL y Python.
- Utilicé CTE, funciones de ventana, rankings y comparaciones temporales.
- Construí seis dashboards en Power BI para análisis ejecutivo, de productos, clientes, territorios y vendedores.
- Apliqué segmentación RFM para agrupar a los clientes según su comportamiento de compra.
- Identifiqué la concentración de ingresos, patrones estacionales y oportunidades de retención.

#### Hallazgos principales

| Área | Hallazgo |
|:---|:---|
| Mezcla de productos | **Las bicicletas generaron aproximadamente el 87.7% de los ingresos.** |
| Estacionalidad | **La primavera generó $29.52 millones.** |
| Territorio principal | **Southwest generó aproximadamente $24 millones.** |
| Desempeño de ventas | **El vendedor con mejor desempeño generó aproximadamente $10.3 millones.** |
| Análisis de clientes | **La segmentación RFM permitió identificar grupos de clientes valiosos y en riesgo.** |

<div align="center">

<img src="dashboards_adventure_works/executive_sales_dashboard.png" alt="Dashboard ejecutivo de ventas de AdventureWorks" width="900">

[**Ver proyecto completo →**](https://github.com/juandguerrero/AdventureWorks-Sales-Analytics-Platform/blob/main/README.md)

</div>

---

## 📈 Análisis de Marketing de LearnLoop

### Análisis del embudo de marketing, adquisición de clientes e ingresos

**SQL · Tableau · Snowflake · dbt · Python · Airflow · AWS S3**

#### Problema de negocio

LearnLoop necesitaba comprender si la inversión publicitaria estaba generando clientes e ingresos, y no solamente clics y sesiones. Creé un flujo de trabajo analítico que conecta la actividad de marketing con datos de CRM, suscripciones, clientes e ingresos.

#### Lo que hice

- Integré datos provenientes de publicidad, sitio web, CRM, suscripciones e ingresos.
- Organicé las transformaciones SQL en capas de **staging, intermediate y marts** utilizando dbt.
- Definí KPI financieros y del embudo, incluyendo tasas de conversión, CAC, ROAS, MRR y ARR.
- Construí dashboards en Tableau para analizar campañas, desempeño del embudo, valor del cliente y cursos.
- Identifiqué inversión ineficiente en marketing y oportunidades para mejorar la conversión.

#### Hallazgos principales

| KPI | Resultado |
|:---|---:|
| Inversión en marketing | **$1.11 millones** |
| Ingresos atribuidos | **$373.5 mil** |
| Retorno de la inversión publicitaria | **0.34x** |
| Costo de adquisición de clientes | **$116.08** |
| Sesiones del sitio web | **740,283** |
| Leads | **93,276** |
| Clientes | **9,592** |
| Conversión de lead a cliente | **10.3%** |

<div align="center">

<img src="dashboards_learnloop/campaign_performance.jpg" alt="Dashboard de desempeño de campañas de LearnLoop en Tableau" width="900">

[**Ver proyecto completo →**](https://github.com/juandguerrero/LearnLoop-Marketing-Analytics-Platform/blob/main/README.md)

</div>

---

## 🛠️ Habilidades técnicas

| Área | Habilidades y tecnologías |
|:---|:---|
| **Análisis de datos** | Análisis exploratorio de datos · Definición de KPI · Análisis de tendencias · Recomendaciones de negocio |
| **SQL** | Joins · CTE · Subconsultas · CASE · Vistas · Funciones de ventana · Validación de datos |
| **Inteligencia de negocios** | Power BI · DAX · Tableau · Looker Studio · Diseño de dashboards |
| **Excel / Sheets** | Tablas dinámicas · XLOOKUP · SUMIFS · COUNTIFS · IF · IFERROR · Limpieza de datos |
| **Python** | pandas · NumPy · Matplotlib · Seaborn · scikit-learn |
| **Modelado de datos** | Esquema estrella · Tablas de hechos y dimensiones · Modelado dimensional |
| **Plataformas de datos** | SQL Server · Snowflake · Databricks · AWS S3 |
| **Transformación y pipelines** | dbt · PySpark · Apache Airflow · ETL/ELT |
| **Conocimiento de negocio** | Operaciones financieras · AP/AR · Conciliaciones · Ingresos · Ventas · Embudos de marketing |
| **Otras herramientas** | Git · GitHub · AppFolio · HubSpot · Jira |

---

## 💼 Experiencia profesional

Antes de enfocarme en el análisis de datos, trabajé durante más de tres años con información contable, financiera y operativa, incluyendo más de un año y medio en el sector de administración de propiedades.

Esa experiencia me enseñó a:

- Trabajar cuidadosamente con grandes volúmenes de datos financieros y operativos.
- Conciliar registros e investigar discrepancias.
- Cumplir fechas límite y mantener documentación precisa.
- Comunicar problemas claramente a los equipos internos.
- Comprender el significado de negocio detrás de las transacciones y los KPI.

Esta experiencia me permite abordar el análisis de datos combinando **curiosidad técnica y contexto de negocio**.

---

## 📫 Contacto

<div align="center">

### Juan David Guerrero Parada

**Analista de Datos Junior | Analítica Financiera y Operativa**

Bucaramanga, Colombia · Disponible para oportunidades remotas

[LinkedIn](https://www.linkedin.com/in/juan-david-guerrero-parada/) · [GitHub](https://github.com/juandguerrero) · [Correo electrónico](mailto:juangrp12@gmail.com)

⭐ Explora los repositorios de los proyectos para consultar los scripts SQL, modelos de datos, dashboards, hallazgos y recomendaciones.

</div>
