# 📦 Data Warehouse – Gestión de Stock (Excelcom)

## 📊 Descripción del Proyecto
Este proyecto consiste en el **diseño de un Data Warehouse para la gestión de stock** en una empresa de servicios IT, con el objetivo de mejorar la planificación de inventarios, reducir el sobre stock y facilitar la toma de decisiones basada en datos.

La solución se apoya en **modelado dimensional**, permitiendo análisis eficientes sobre inventario, ventas y compras desde una perspectiva de negocio.

---

## 🏢 Contexto del Negocio
Excelcom es una empresa dedicada a la comercialización e integración de tecnología, con más de 20 años de trayectoria en el mercado.  
Como resultado de su crecimiento y la falta de planificación basada en demanda, la empresa acumuló **exceso de inventario**, lo que generó:

- Capital inmovilizado  
- Altos costos de almacenamiento  
- Baja visibilidad sobre la evolución del stock  

---

## ❗ Definición del Problema
La empresa enfrenta una **gestión ineficiente del stock de equipamiento y componentes informáticos**, provocando sobre stock y una inmovilización de capital superior a los niveles recomendados.

---

## 🎯 Objetivos del Proyecto

### Objetivo Principal
- Reducir en un **10% el capital inmovilizado** en el plazo de un año mediante una gestión más eficiente del stock.

### Objetivos Secundarios
- Mejorar la disponibilidad y calidad de información sobre:
  - Inventarios
  - Ventas
  - Compras

---

## 🧱 Arquitectura del Data Warehouse

### 📌 Diagrama Conceptual
Representa las principales entidades del negocio y sus relaciones, enfocándose en **inventario, ventas y compras** desde una perspectiva analítica.

![Diagrama Conceptual del Data Warehouse](images/diagrama_conceptual.png)

---

### 📌 Diagrama Lógico
Modelo lógico basado en **esquema en estrella**, con tablas de hechos y dimensiones optimizadas para consultas analíticas y herramientas de BI.

![Diagrama Lógico del Data Warehouse](images/diagrama_logico.png)

---

## 📐 Diseño del Data Warehouse

### Enfoque de Modelado
- **Modelado dimensional (Star Schema)**
- Separación entre **tablas de hechos** y **tablas de dimensiones**
- Optimizado para análisis y reporting

### Tablas de Hechos
- **Hecho Inventario**
- **Hecho Ventas**
- **Hecho Compras**

### Dimensiones Principales
- Tiempo  
- Producto  
- Categoría de producto  
- Región  
- Depósito  
- Proveedor  

---

## 📊 Capacidades Analíticas

### Análisis de Inventario
- Stock disponible por:
  - Depósito
  - Mes
  - Categoría de producto
- Promedio histórico de stock por categoría, mes y depósito

### Análisis de Ventas
- Cantidad de productos vendidos por región y mes
- Promedio mensual de ventas por región
- Top 3 categorías de productos vendidas por valor ($), por región y mes

### Análisis de Compras
- Cantidad de productos comprados por región, mes y proveedor
- Clasificación de productos según valor de compra:
  - **Bajo valor:** < USD 500  
  - **Valor medio:** USD 500 – USD 2000  
  - **Alto valor:** > USD 2000  
- Promedio mensual de compras por categoría
- Top 3 categorías compradas por valor ($), por región

---

## 🧠 Valor para el Negocio
El Data Warehouse permite:

- Mejor planificación de la demanda  
- Reducción del sobre stock  
- Optimización de decisiones de compra  
- Análisis histórico confiable  
- Gestión de inventarios basada en KPIs  

---

## 🛠 Herramientas y Habilidades Aplicadas
- SQL  
- Diseño de Data Warehouse  
- Modelado Dimensional  
- Análisis de Negocio  
- Definición de KPIs  
- Analítica de Inventarios  

---

## 👥 Equipo de Trabajo
- Santiago Nieto  
- Oscar Marasca  
- Aitor Ortuño Rossetto  
- Romina Salinas  
- Daniel Simosa  

---

## 📌 Notas
Este proyecto se centra en el **diseño analítico y el modelado de datos**, sentando las bases para futuros procesos de ETL y la construcción de dashboards en herramientas de BI.

---

📬 Para consultas o colaboraciones, podés contactarme vía LinkedIn.

