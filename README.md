# 📊 Proyecto Telecom X Parte 1

Este proyecto tiene como objetivo analizar las cancelaciones de servicios en una empresa de telecomunicaciones, identificando patrones relevantes y posibles factores que influyen en la decisión de los clientes de abandonar el servicio.

  
---

## 🎯 Propósito del Análisis.  

El análisis busca responder preguntas clave como:

- ¿Qué factores están asociados con una mayor tasa de cancelación?
- ¿Qué características comparten los clientes que permanecen activos?
- ¿Cómo pueden usarse estos hallazgos para reducir la pérdida de clientes?

---

## 🗂️ Estructura del Proyecto

TelecomX/
│

├── data/ # Datos en bruto y limpios

│ 
  ├── raw_data.csv

│
  └── clean_data.csv
│

├── notebooks/ # Notebooks de análisis. 

│
└── telecom_analysis.ipynb
│
├── 
   images/ # Gráficos exportados desde el análisis

│ 
    ├── churn_by_contract.png

│
    └── heatmap_correlation.png
│
├── 
   README.md # Documentación del proyecto

└── requirements.txt # Dependencias del entorno

---


## 🧪 Instrucciones para Ejecutar el Notebook

1. Clona este repositorio:
   ```bash
   git clone https://github.com/MacarenaQuijadaG/Challenge_Telecom.git


   cd TelecomX
   
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
  
3. Abre el Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/TelecomX_LATAM.ipynb

4. Ejecuta las celdas paso a paso para explorar los análisis y gráficos.

---
## 🧠 Conclusión
Este proyecto proporciona una base sólida para entender el comportamiento de cancelación en servicios de telecomunicaciones. Los resultados pueden ser usados por el equipo de marketing o retención para diseñar estrategias de fidelización efectivas.


