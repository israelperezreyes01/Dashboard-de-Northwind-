# 📈 Dashboard de Ventas: Northwind Traders

![Power BI](https://img.shields.io/badge/Tools-Power%20BI-yellow)
![Status](https://img.shields.io/badge/Status-Completado-success)

## 📖 Descripción del Proyecto
Este proyecto consiste en un dashboard interactivo desarrollado en **Power BI** utilizando la base de datos clásica de **Northwind**. El objetivo es transformar datos transaccionales en información estratégica para la toma de decisiones sobre ventas, productos y desempeño de empleados.

---

## 📊 Secciones del Dashboard
El reporte incluye análisis detallados en las siguientes áreas:
* **Resumen de Ventas:** Evolución temporal de los ingresos y cumplimiento de metas.
* **Análisis de Productos:** Identificación de los artículos más vendidos y categorías con mayor margen.
* **Desempeño Logístico:** Tiempos de envío y análisis de proveedores.
* **Gestión de Clientes:** Segmentación geográfica y comportamiento de compra.

---

## 🛠️ Procesamiento de Datos (ETL)
Para la construcción de este archivo `.pbix` se realizaron los siguientes pasos:
1.  **Extracción:** Conexión a la base de datos Northwind.
2.  **Transformación (Power Query):** * Limpieza de valores nulos y normalización de tipos de datos.
    * Creación de columnas personalizadas para análisis de fechas.
3.  **Modelado:** * Implementación de un esquema en estrella (*Star Schema*).
    * Creación de una Tabla de Calendario para análisis de inteligencia de tiempo.
4.  **Medidas DAX:** Creación de indicadores clave (KPIs) como *Total Sales*, *Year-over-Year Growth* y *Profit Margin*.

---

## 🚀 Cómo visualizar el reporte
1.  Descarga el archivo `Northwind.pbix` de este repositorio.
2.  Abre el archivo con **Power BI Desktop**.
3.  Si deseas ver una versión estática, consulta la carpeta `/screenshots` de este repositorio (opcional).

---

## 💡 Hallazgos Principales
* **Tendencia:** Se identificó un crecimiento del X% en el último trimestre.
* **Top Clientes:** Los clientes en la región [Región] representan el mayor volumen de facturación.
* **Optimización:** Ciertos productos muestran una baja rotación de inventario, sugiriendo una revisión de stock.

---

## ✒️ Autor
* **Santiago Pérez** 
