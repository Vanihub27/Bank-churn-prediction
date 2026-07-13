<p align="center">
  <img src="images/banner.png" alt="Bank Churn Prediction" width="100%">
</p>

# 🏦 Bank Churn Prediction

> **Pipeline End-to-End de Machine Learning para predecir el abandono de clientes bancarios y generar estrategias de retención basadas en datos.**

<br>

<p align="center">

📈 **Churn:** 20.4% &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
🎯 **Mejor modelo:** Stacking &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
📊 **ROC-AUC:** 0.87 &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
👥 **Dataset:** 10.000 clientes &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
🤖 **Modelos:** 6

</p>

---

## 🛠 Tecnologías

<p>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">

<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">

<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">

<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">

<img src="https://img.shields.io/badge/XGBoost-EC6B23?style=for-the-badge">

<img src="https://img.shields.io/badge/LightGBM-7CB342?style=for-the-badge">

<img src="https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge">

<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge">

<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge">

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">

<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">

</p>

---

# 📌 Descripción

La pérdida de clientes (*Customer Churn*) representa uno de los principales desafíos para las entidades financieras, ya que impacta directamente sobre el **Customer Lifetime Value (CLV)**, los costos de adquisición y la rentabilidad del negocio.

En este proyecto se desarrolló un pipeline completo de Ciencia de Datos para identificar clientes con riesgo de abandono mediante técnicas de Machine Learning supervisado y no supervisado.

Más allá del desempeño predictivo, el objetivo fue transformar los resultados del modelo en **insights accionables** que permitan optimizar estrategias de retención de clientes.

---

# 🎯 Objetivos

- Predecir la probabilidad de abandono de clientes.
- Comparar distintos algoritmos de clasificación.
- Identificar las variables con mayor impacto en el churn.
- Segmentar clientes según su comportamiento.
- Traducir métricas técnicas en recomendaciones para negocio.

---

# 🔄 Pipeline del proyecto

```mermaid
flowchart LR

A[Dataset Bancario] --> B[EDA y Limpieza]

B --> C[Ingeniería de Variables]

C --> D[Modelos Supervisados]

D --> E[Evaluación de Modelos]

E --> F[Segmentación K-Means]

F --> G[Insights de Negocio]

G --> H[Recomendaciones Estratégicas]
