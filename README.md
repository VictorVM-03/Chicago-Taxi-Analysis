# 🚕 Análisis de Movilidad Urbana: Taxis en Chicago

## 📊 Contexto del Proyecto
Este proyecto analiza el ecosistema de transporte en Chicago utilizando datos de noviembre de 2017. El objetivo es proporcionar una visión estratégica para la empresa **Zuber** sobre los patrones de demanda y el impacto del clima en la eficiencia operativa.

---

## 🛠️ Metodología y Herramientas
* **Lenguaje:** Python
* **Librerías:** Pandas, Matplotlib, Seaborn, SciPy.
* **Análisis Exploratorio (EDA):** Identificación de los 10 barrios con mayor demanda (*hotspots*) y las empresas con mayor volumen de viajes.
* **Estadística:** Implementación de pruebas de hipótesis para comparar la duración de los viajes en diferentes condiciones climáticas.

---

## 📈 Resultados Clave
1.  **Dominio de Mercado:** Se identificó una alta concentración del mercado, con una empresa líder superando significativamente al resto de los competidores.
2.  **Nodos Logísticos:** Los barrios de **Loop, River North y Streeterville** concentran la mayor parte de la demanda, lo que sugiere priorizar la flota en estas zonas.
3.  **Impacto Climático:** Se confirmó mediante una **prueba T de Student** que el clima adverso afecta significativamente la duración de los viajes al aeropuerto O'Hare ($p\text{-value} < 0.05$), incrementando el tiempo de traslado en aproximadamente **7 minutos** promedio.

---

## 💡 Recomendaciones Estratégicas
* **Tarifas Dinámicas:** Implementar un sistema de precios variables durante condiciones climáticas adversas para compensar el incremento en la duración del viaje.
* **Optimización de Flota:** Focalizar campañas de captación de conductores en los barrios del "Top 10" de demanda para reducir tiempos de espera y maximizar viajes.

---
**Desarrollado por:** [VictorVM-03](https://github.com/VictorVM-03)
