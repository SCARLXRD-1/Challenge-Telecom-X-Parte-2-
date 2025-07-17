# 📊 Análisis de Churn para Telecom X

## 📌 Descripción del Proyecto  
Este repositorio contiene un análisis completo de *churn* (rotación de clientes) realizado para una empresa ficticia de telecomunicaciones, **Telecom X**, como parte del programa **Challenge ONE – Data Science**.  
El objetivo principal es identificar los factores que influyen en la cancelación del servicio por parte de los clientes y proponer estrategias basadas en datos para mejorar su retención.

---

## 🎯 Objetivo  
Aplicar técnicas de análisis de datos utilizando Python y sus principales bibliotecas para:
- Procesar y explorar los datos de clientes.
- Extraer *insights* valiosos sobre el comportamiento de abandono.
- Apoyar al equipo de Data Science en la creación de modelos predictivos.
- Diseñar estrategias efectivas para reducir la tasa de *churn*.

---

## 🔍 Contenido del Análisis

1. **Importación de bibliotecas**  
   Uso de herramientas clave como `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `requests`, `json` y `plotly` para procesamiento y visualización de datos.

2. **Carga y exploración del dataset**  
   Lectura del conjunto de datos desde un archivo JSON alojado en GitHub y análisis inicial de su estructura.

3. **Limpieza y preprocesamiento**  
   - Tratamiento de valores nulos.  
   - Normalización y transformación de variables categóricas.  
   - Preparación del dataset para análisis estadístico.

4. **Análisis exploratorio de datos (EDA)**  
   - Cálculo de asociaciones entre variables (V de Cramér, Pearson).  
   - Visualizaciones de distribución y relación con el *churn*.  
   - Análisis del *Customer Lifetime Value (CLV)*.

5. **Ingeniería de características**  
   - Creación de nuevas variables: `NumServices`, `TenureGroup`, `PremiumCustomer`.

6. **Análisis combinado de factores**  
   - Evaluación del *churn* según múltiples combinaciones de variables (heatmaps interactivos).

7. **Insights clave**  
   - Identificación de factores que elevan o reducen la tasa de cancelación.

8. **Conclusiones y recomendaciones**  
   - Interpretación de resultados.  
   - Propuestas estratégicas para reducir el *churn* basadas en los hallazgos.

---

## 🛠️ Herramientas y Bibliotecas Utilizadas

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scipy`  
- `requests`  
- `json`  
- `plotly`

---

## 💡 Principales Hallazgos

- Los clientes con contratos **mensuales** presentan una tasa de *churn* del **42%**, significativamente mayor que aquellos con contratos **anuales (11%)** o **bianuales (3%)**.
- La **ausencia de servicios** como `OnlineSecurity` y `TechSupport` aumenta el riesgo de cancelación en más de un **35%**.
- Los **primeros 12 meses** de relación con el cliente son críticos, especialmente en usuarios mayores de **65 años**.

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/nombre_repositorio.git
