# 📊 ds-top10_sales_vs_profit  
**Análisis de los Productos Más Vendidos y Menos Rentables**  

## 📋 Descripción del Proyecto  
Este proyecto tiene como objetivo analizar:  
1. Los **10 productos con mayores ventas** y evaluar su **utilidad** para identificar aquellos que, a pesar de venderse en grandes volúmenes, podrían tener márgenes de ganancia bajos.  
2. Los **10 productos con menor utilidad** y revisar sus **volúmenes de ventas**, lo que permite detectar productos con márgenes de ganancia reducidos que podrían beneficiarse de estrategias de promoción o ajuste de precios.  

El análisis proporciona una visión integral que facilita la optimización de precios, la maximización de la rentabilidad y la identificación de oportunidades para aumentar ingresos o reducir costos.  


El sistema procesa **reportes mensuales de ventas y compras** en formato Excel, consolidando los datos y generando reportes visuales y tabulares. La salida incluye:  
- **📊 Archivos Excel** con los datos procesados y analizados.  
- **📄 PDFs personalizados** con gráficos y tablas diseñados para diferentes departamentos, facilitando la interpretación y la toma de decisiones.  

Mediante este análisis, se genera información clave que proporciona:  
- **📈 Volumen de ventas por producto.**  
- **💸 Margen de ganancia asociado a cada producto.**  
- **🔍 Comparación de ventas vs rentabilidad** para identificar desequilibrios y productos poco rentables.  

---

## 🚀 Beneficios Clave  
- **Identificación rápida** de productos con alto volumen pero baja rentabilidad.  
- **Optimización de márgenes** mediante reportes segmentados por departamento.  
- **Automatización del análisis** para ahorrar tiempo en la generación de reportes.  
- **Visualización clara** que facilita la toma de decisiones estratégicas.  

---

## 🛠️ Herramientas Utilizadas  
- **Python** – Procesamiento de datos y automatización de reportes.  
  - **Pandas** – Manipulación y análisis de datos.  
  - **OpenPyXL** – Generación de reportes en Excel.  
  - **FPDF / ReportLab** – Creación de reportes PDF personalizados.  
- **Excel** – Entrada de datos (reportes de ventas y compras).  

---

## 📂 Componentes del Proyecto  
1. **Reportes de Ventas (Excel):** Archivos mensuales con datos de ventas por producto y almacén.  
2. **Reporte de Compras (Excel):** Listado de compras realizadas durante el mes.  
3. **Salida:**  
   - **Excel consolidado** con los 10 productos más vendidos y menos rentables.  
   - **PDFs personalizados** con gráficos y tablas para departamentos clave.  

---

## 🔧 Cómo Ejecutar el Proyecto  
1. **Ubica los reportes de ventas y compras** en la carpeta `input/`.  
2. **Ejecuta el script principal:**  
   ```bash
   python main.py
