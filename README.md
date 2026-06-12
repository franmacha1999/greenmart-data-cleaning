# 🛒 GreenMart — Limpieza y Transformación de Datos

Proyecto de data engineering desarrollado como parte de la beca en **Nexeus Big Data**.

---

## 📋 Descripción

GreenMart Retail necesitaba un dataset limpio y normalizado para soportar futuros análisis de clientes, productos, inventario y marketing. Este proyecto toma el archivo fuente `greenmart_customers_products.csv` y produce un dataset limpio y validado listo para análisis.

---

## 📁 Archivos del repositorio

| Archivo | Descripción |
|---|---|
| `limpieza_y_transformacion_greenmart.ipynb` | Notebook completo con todo el flujo de limpieza |
| `greenmart_customers_products_clean.csv` | Dataset limpio exportado |
| `informe_greenmart.pdf` | Informe final del proyecto |

---

## 🔄 Flujo del proyecto

1. **Carga e inspección** — estructura, tipos de datos, nulos y duplicados
2. **Perfilado de calidad** — diagnóstico completo de problemas
3. **Estrategia de limpieza** — decisiones documentadas antes de transformar
4. **Limpieza** — deduplicación, conversión de tipos, imputación y normalización de texto
5. **Validación** — verificación de `total_spent` y detección de outliers con IQR
6. **Exportación** — CSV limpio con verificación de integridad

---

## 📊 Resultados principales

| Métrica | Antes | Después |
|---|---|---|
| Filas | 10.400 | 10.033 |
| Filas duplicadas | 367 | 0 |
| Nulos en datos de cliente | 722 | 0 |
| Errores en total_spent | No verificado | 0 |
| Columnas | 11 | 15 (+4 flags de outliers) |

---

## 🛠️ Tecnologías utilizadas

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- Google Colab

---

## ▶️ Cómo ejecutar el notebook

1. Abrís el archivo `.ipynb` en Google Colab
2. Subís el archivo `greenmart_customers_products.csv` cuando se solicite
3. Ejecutás **Entorno de ejecución → Reiniciar y ejecutar todo**
4. El CSV limpio se genera automáticamente al finalizar

---

## 👤 Autor
 Franco Macharette Baez 
Proyecto desarrollado como entrega de beca — **Nexeus Big Data · 2026**
