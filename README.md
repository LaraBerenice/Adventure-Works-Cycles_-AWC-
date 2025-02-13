# 📌 Adventure Works Cycles (AWC) - Análisis de Ventas con Power BI

## 📖 Introducción
Adventure Works Cycles (AWC) es una empresa multinacional dedicada a la fabricación y distribución de bicicletas, piezas y accesorios en los mercados de Norteamérica, Europa y Asia. Con 500 empleados y diversos equipos de ventas regionales, enfrenta el reto de no contar con indicadores óptimos para la toma de decisiones estratégicas.

El objetivo de este proyecto es realizar un análisis de ventas sistematizado mediante Power BI, proporcionando métricas y visualizaciones interactivas para mejorar la eficiencia en la toma de decisiones.

## 🎯 Objetivos del Proyecto
✔ **Mejorar la calidad de los datos** mediante limpieza y transformación.  
✔ **Construir un modelo de datos** relacional alineado con las necesidades del negocio.  
✔ **Aplicar DAX** para el cálculo de métricas clave.  
✔ **Diseñar dashboards** intuitivos y atractivos para facilitar la interpretación de datos.  

## 🚀 Desarrollo del Proyecto

### 🔹 AVANCE 1: Conexión y Limpieza de Datos
Se realizó la extracción, limpieza y transformación de datos provenientes de la base `AdventureWorksDW2019` en SQL Server. Se optimizó la estructura eliminando datos innecesarios, corrigiendo errores y asegurando la coherencia de las tablas de dimensión y hechos.

### 🔹 AVANCE 2: Creación del Modelo Relacional
Se diseñó un modelo estrella, estableciendo relaciones entre:

- **Dimensiones**: Productos, Clientes, Geografía, Fecha, Promociones.  
- **Hechos**: Ventas por Internet y Resellers.  

Se deshabilitó la carga de tablas auxiliares para mejorar el rendimiento.

### 🔹 AVANCE 3: Generación de Medidas y Columnas Calculadas
Se implementaron medidas en **DAX** para analizar KPIs clave como:

- **Ventas Totales** 💲  
- **Descuentos Aplicados** 📉  
- **Cantidad de Productos Vendidos** 🚴  
- **Impuestos y Fletes** 📊  

### 🔹 AVANCE 4: Creación del Dashboard en Power BI
Se diseñó un dashboard interactivo, organizado en secciones que permiten visualizar:  

📌 **Tendencias de ventas** por período y región.  
📌 **Comparación de productos más vendidos**.  
📌 **Impacto de promociones** en el rendimiento comercial.  
📌 **Análisis geoespacial de clientes y ventas**.  

<div align="center">
  <img src="./Imagenes/Captura%20de%20pantalla%202024-11-03%20180859.png" alt="Descripción de la imagen" width="800" />
</div>## 🔍 Conclusiones y Aprendizajes
El desarrollo de este proyecto permitió comprender la importancia del análisis de datos en la toma de decisiones empresariales. Se logró transformar datos crudos en insights valiosos, optimizando la gestión de ventas de **AWC** mediante visualizaciones claras y dinámicas.

📌 **Futuras mejoras:**  
Se podrían integrar datos en tiempo real, optimizar el modelo con más variables y mejorar la interactividad del dashboard.

## 📎 Información Adicional  
📌 **Desarrollado por:** *Ledesma Lara Berenice*  
📆 **Fecha de entrega:** 10 de julio de 2024  
🏫 **Institución:** *Academia Henry – Bootcamp Data Analytics*  



