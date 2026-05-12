<img width="1659" height="948" alt="image" src="https://github.com/user-attachments/assets/10edeb96-43c2-4aa8-8711-3c4cbdf25ff6" />


# Cyber Threat Log Analyzer

## 📌 Descripción General
Cyber Threat Log Analyzer es una aplicación desarrollada con Python y Streamlit para el análisis de logs de seguridad y detección de actividad sospechosa en redes.

El proyecto combina técnicas de ciencia de datos, visualización interactiva y machine learning para facilitar el análisis de eventos de ciberseguridad, permitiendo identificar patrones anómalos, actividad maliciosa y comportamientos sospechosos a partir de registros de red.

La aplicación está diseñada para trabajar con archivos CSV de eventos de seguridad y ofrecer una interfaz dinámica e intuitiva para explorar grandes volúmenes de datos de forma visual y eficiente.

---

# 🚀 Funcionalidades Principales

## 📊 Análisis de Logs
- Procesamiento y análisis de eventos de red
- Agrupación de eventos por hora, categoría y protocolo
- Identificación de patrones y picos de actividad
- Exploración de datos mediante filtros dinámicos

## 📈 Visualización Interactiva
- Dashboard interactivo desarrollado con Streamlit
- Gráficos dinámicos con Plotly y Matplotlib
- Heatmaps y gráficos temporales
- Visualización de eventos sospechosos en tiempo real

## 🕵️ Detección de Amenazas
- Identificación de IPs maliciosas
- Filtrado de eventos sospechosos
- Clasificación automática de eventos
- Detección de anomalías mediante machine learning

## ⏱️ Análisis Temporal
- Agrupación de eventos por intervalos de tiempo
- Detección de horas con mayor actividad
- Identificación de patrones repetitivos y comportamientos anómalos

## ⚙️ Interfaz Interactiva
- Carga dinámica de archivos CSV
- Filtros personalizados por:
  - Tipo de ataque
  - Categoría
  - Protocolo
  - IP origen/destino
  - Hora del evento
- Actualización automática de visualizaciones

---

# 🛠️ Tecnologías Utilizadas

## Lenguaje y Desarrollo
- Python
- Streamlit

## Análisis de Datos
- Pandas
- NumPy

## Machine Learning
- Scikit-learn

## Visualización
- Plotly
- Matplotlib

---

# 🗂️ Estructura del Proyecto

```bash
CyberThreatLogAnalyzer/
├── app.py
├── data/
├── assets/
├── models/
├── pages/
├── utils/
├── visualizations/
├── preprocessing/
├── requirements.txt
└── README.md
```

---

# 📊 Dataset Utilizado

El proyecto utiliza datasets de logs de seguridad que contienen información relacionada con eventos de red, incluyendo:

- Fecha y hora del evento
- Categoría y subcategoría
- Dirección IP origen y destino
- Protocolos de red
- Tipo de evento
- Mensajes de logs

---

# ⚙️ Instalación

## Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/cyber-threat-log-analyzer.git
cd cyber-threat-log-analyzer
```

## Crear entorno virtual

### Windows
```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS
```bash
source venv/bin/activate
```

## Instalar dependencias

```bash
pip install -r requirements.txt
```

---

# ▶️ Ejecución

```bash
streamlit run app.py
```

La aplicación estará disponible en:

```bash
http://localhost:8501
```

---

# 🎯 Objetivo del Proyecto

El objetivo principal es aplicar técnicas de ciencia de datos y machine learning al ámbito de la ciberseguridad, utilizando análisis de logs para detectar comportamientos anómalos y facilitar la interpretación de eventos de red.

Este proyecto fue desarrollado como parte de un curso de Ciencia de Datos con Python, integrando conocimientos de análisis de datos, visualización interactiva y detección de amenazas en un entorno práctico.

---

# 📚 Aprendizajes Obtenidos

Durante el desarrollo del proyecto se trabajó en:

- Limpieza y transformación de datos
- Análisis exploratorio de datos (EDA)
- Visualización interactiva
- Detección de anomalías
- Clasificación de eventos
- Desarrollo de dashboards con Streamlit
- Aplicación de machine learning en ciberseguridad


