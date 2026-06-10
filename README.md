# 📈 Análisis de Rendimiento Comercial y BI - Ventas Retail

## 📝 Descripción del Proyecto
Este proyecto consiste en un análisis exploratorio de datos (EDA) y desarrollo de Inteligencia de Negocios utilizando **Python** y **Pandas**. El objetivo principal es evaluar el comportamiento transaccional de múltiples tiendas retail, identificar los productos estrella de cada sucursal, medir la eficiencia de los vendedores y descubrir patrones estacionales de compra para optimizar la toma de decisiones estratégicas.

---

## 📊 KPIs y Métricas Clave Descubiertas
A través del procesamiento del dataset, se determinaron las siguientes métricas globales de rendimiento operativo:
* **Ticket Promedio de Compra:** `$4,070.29` por transacción.
* **Unidades Promedio por Transacción (UPT):** `5.4 unidades` por cliente.
* **Precio Promedio de Productos:** `$751.21`

---

## 📂 Estructura del Repositorio
* `data/`: Contiene el set de datos en formato CSV con el histórico de ventas.
* `notebooks/`: Incluye el Jupyter Notebook desarrollado originalmente en Kaggle con todo el flujo de extracción, limpieza con codificación `latin1` y visualizaciones.

---

## 🛠️ Tecnologías y Librerías Utilizadas
* **Python 3.12**
* **Pandas:** Limpieza de datos, manejo de codificación de caracteres, tablas dinámicas (`pivot_table`) y agregaciones avanzadas (`groupby`).
* **Matplotlib & Seaborn:** Creación de gráficos analíticos (Líneas de crecimiento acumulado, subplots compactos y mapas de calor correlacionales).
---

---

## 💡 Conclusiones del Análisis
1. **Dominio de Sucursales:** La **Tienda E** lidera los ingresos globales con un total vendido superior, seguida muy de cerca por la Tienda D, mientras que la Tienda C presenta el menor volumen de facturación transaccional.
2. **Fuerza de Ventas:** Los vendedores *José* y *Pedro* representan los pilares comerciales con la mayor recaudación e ingresos totales generados para el negocio.
3. **Análisis de Concentración:** El mapa de calor permitió identificar con precisión qué departamentos o categorías de producto sostienen el tráfico de clientes en cada sucursal específica.

---
