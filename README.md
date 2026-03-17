# 📞 Predicción de Abandono de Clientes - Interconect

## 📝 Escenario de Negocio
El operador de telecomunicaciones **Interconect** busca prevenir la fuga de sus clientes. Para ello, el equipo de marketing necesita identificar a los usuarios que planean cancelar sus planes para ofrecerles cupones promocionales y opciones de fidelización.

## 🛠️ Metodología y Solución
En este proyecto, procesé los datos personales de los clientes, información sobre sus tarifas y contratos para construir un modelo de clasificación:
- **Análisis de Datos:** Identificación de patrones de comportamiento y servicios con mayor tasa de cancelación.
- **Modelado:** Implementación de modelos avanzados como **CatBoost** y **Random Forest**.
- **Métrica Principal:** Se optimizó el modelo para alcanzar un **AUC-ROC** competitivo, asegurando una alta capacidad de discriminación entre clientes leales y en riesgo.

## 📊 Hallazgos de Interconect
- Se detectó que ciertos tipos de contratos influyen directamente en la retención.
- La integración de servicios adicionales (Internet, Telefonía) juega un papel clave en la lealtad del usuario.

## 🧰 Stack Técnico
`Python`, `Pandas`, `CatBoost`, `Scikit-Learn`, `Seaborn`.
