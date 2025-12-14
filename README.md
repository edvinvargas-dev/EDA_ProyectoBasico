# 📊 Análisis Exploratorio de Datos (EDA) – Ventas Foodservice Guatemala  
**Dataset sintético de 50,000 registros | Periodo 2023–2024**

Este proyecto presenta un análisis exploratorio de datos (EDA) de un dataset sintético que simula el comportamiento real de una empresa de distribución Foodservice en Guatemala.  
El objetivo principal es comprender patrones de venta por categoría, canal, zona geográfica, productos y clientes, así como identificar oportunidades estratégicas para el negocio.

---

## 🔍 **Objetivos del Proyecto**

- Analizar el comportamiento mensual de ventas.
- Identificar las categorías más importantes dentro del portafolio.
- Evaluar el aporte de cada canal de distribución (HORECA, Retail, Mayorista).
- Estudiar el desempeño por zona geográfica.
- Identificar productos y clientes clave.
- Generar conclusiones ejecutivas útiles para toma de decisiones.

---

## 🧰 **Tecnologías Utilizadas**

- **Python 3**
- **pandas** — manipulación de datos  
- **numpy** — cálculos numéricos  
- **matplotlib** — visualización básica  
- **Jupyter Notebook** — desarrollo y análisis interactivo  

---

## 📁 **Descripción del Dataset**

El dataset contiene **50,000 registros** entre 2023 y 2024, con la siguiente estructura:

- `fecha`
- `sku`
- `producto`
- `categoria`
- `cliente`
- `canal` (HORECA, Retail, Mayorista)
- `zona`
- `precio_unitario`
- `cantidad`
- `costo_unitario`
- `margen_unitario`
- `total_venta`
- `total_costo`
- `total_margen`

Las categorías incluidas abarcan Proteínas, Papas & Appetizers, Procesados, Grasas y Aceites, Bebidas, Papel y Empaques.

---

## 📈 **Principales Análisis Realizados**

### ✔ **1. Análisis temporal (ventas mensuales)**  
Evaluación del comportamiento de ventas entre 2023–2024. Se identifican patrones de estabilidad y meses con picos de demanda.

### ✔ **2. Ventas por categoría**  
Determinación del peso de cada línea de producto para identificar prioridades de inventario y oportunidades de crecimiento.

### ✔ **3. Ventas por canal**  
Clasificación HORECA, Retail y Mayorista para comprender la concentración comercial del negocio.

### ✔ **4. Ventas por zona geográfica**  
Evaluación territorial que permite analizar oportunidades en regiones débiles y fortalecer zonas clave.

### ✔ **5. Top productos y top clientes**  
Identificación de los principales generadores de ingresos.

---

## 🧠 **Conclusiones Ejecutivas**

### **1. Estabilidad mensual**
Las ventas se mantienen en un rango de **Q 650,000 – Q 780,000**, mostrando estabilidad sin estacionalidad fuerte.

### **2. Categorías dominantes**
- **Grasas y Aceites** lideran con más de Q 5M  
- Le siguen **Proteínas** y **Procesados**  
- Papel y Empaques tienen potencial de cross-selling

### **3. Canal estratégico**
- **HORECA** es el principal impulsor del negocio  
- Retail tiene peso medio  
- Mayorista presenta oportunidad de expansión

### **4. Distribución geográfica equilibrada**
Las zonas tienen ventas cercanas entre sí, destacando:  
Huehuetenango, Izabal y Alta Verapaz.  
Las zonas más bajas (como Baja Verapaz) representan oportunidades de desarrollo.

### **5. Productos estrella**
El **Aceite vegetal 20L** es el líder absoluto en ventas, seguido por filetes de pescado, pechuga de pollo y jamón de pavo.

### **6. Clientes clave**
Hoteles, restaurantes y algunos retail medianos impulsan la mayor parte del volumen.

---

## 🚀 **Recomendaciones Estratégicas**

- Priorizar inventario y disponibilidad de productos esenciales (Aceite vegetal, proteínas).  
- Expandir productos complementarios (Papel, Empaques, Bebidas).  
- Fortalecer estrategias comerciales para HORECA.  
- Analizar oportunidades de crecimiento en zonas de menor volumen.  
- Continuar con análisis avanzados:  
  - Clasificación ABC  
  - Segmentación de clientes (K-Means)  
  - Forecasting (ARIMA, Prophet)  
  - Modelos predictivos de ventas

---

## ▶️ **Cómo Ejecutar Este Proyecto**

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repo.git
