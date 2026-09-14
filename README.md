# 📊 Análisis del Fondo FORTAMUN - Área Metropolitana de Guadalajara

Análisis analítico aplicado a los gastos ejecutados con recursos públicos del **Fondo de Aportaciones para de los Municipios (FORTAMUN)** en 9 municipios del Área Metropolitana de Guadalajara. 

El objetivo principal es evaluar la integridad de los datos financieros, identificar patrones atípicos y detectar posibles anomalías operativas mediante técnicas estadísticas avanzadas.

---

## 🛠️ Metodología y Herramientas Estadísticas
* **Ley de Benford:** Modelado del comportamiento de los primeros dígitos para contrastar la distribución de frecuencias empíricas frente a la teórica.
* **Prueba de Chi-cuadrada ($\chi^2$):** Evaluación global de bondad de ajuste para determinar la significancia estadística de las desviaciones.
* **Pruebas de Z-score Individual:** Identificación puntual de dígitos sobrerrepresentados que actúan como banderas rojas (*red flags*) analíticas.

## 📁 Estructura del Repositorio
El análisis se encuentra distribuido en los siguientes Jupyter Notebooks:
* `FORTAMUN_LdM.ipynb` – Análisis descriptivo auditoría de anexos de gastos y desglose de registros ambiguos por proveedor del municipio Lagos de Moreno.
* `FORTAMUN_municipios_GDL.ipynb` – Análisis descriptivo detallado, auditoría de anexos de gastos y desglose de registros ambiguos por proveedor de 9 municipios del Área Metropolitana de Guadalajara.

## 🔍 Hallazgos Clave
* **Distribución Anómala:** Detección de frecuencias de dígitos que divergen significativamente de la Ley de Benford en ciertos municipios.
* **Ambigüedad en Control Interno:** Identificación de registros idénticos bajo el concepto de *"Gastos varios"*, limitando la trazabilidad del gasto público y la correcta rendición de cuentas.
