# 📊 Migración de Archivos CSV a BigQuery y Visualización en Dashboard

Este proyecto fue desarrollado como parte del **proyecto final del curso de Ingeniería de Datos en Google Cloud Platform (GCP)**. Consiste en la migración de datos desde archivos CSV hacia BigQuery, para luego analizarlos mediante un dashboard interactivo creado con una herramienta de visualización llamado Looker Studio.

---
## 🚀 Descripción General

La solución se basa en un flujo de trabajo de ingeniería de datos que incluye:

- Limpieza y transformación de archivos CSV con Python.
- Carga de los datos procesados a Google BigQuery.
- Conexión del dataset en BigQuery con una herramienta de visualización (Looker Studio).
- Creación de un dashboard interactivo con métricas clave.
---

## 🛠 Tecnologías Utilizadas

- **Python 3.10+**
- **pandas**
- **Google BigQuery**
- **Looker Studio**
- **Jupyter Notebook realizado en Visual Studio Code**
---

## 🗂 Estructura del Proyecto
📁 csv_marketing/ → Archivos CSV fuente

📁 notebook/ → Código de migración y transformación (ETL)

📁 presentacion/ → Presentacion del proyecto y el Dashboard realizado en Looker Studio

📄 README.md → Documentación del proyecto

📌 Requisitos para Ejecutarlo
Cuenta en Google Cloud Platform (con BigQuery habilitado).
Llave publica - lo puedes sacar a traves de IAM y reemplazarlo en el codigo.

## 🔧 Cómo Usar este Proyecto

Sigue estos pasos para clonar el repositorio y ejecutar el proyecto localmente:

### 1. Clonar el repositorio

```bash
git clone https://github.com/JherCruz18/MigracionNube.git
