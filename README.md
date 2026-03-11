# Análisis de Retención de Clientes (Churn) - TelecomX Latam 📡

Este repositorio contiene un análisis detallado sobre el abandono de clientes (**Churn**) para una empresa de telecomunicaciones en Latinoamérica. El objetivo es identificar patrones de comportamiento, preprocesar datos para modelos de Machine Learning y proponer estrategias de negocio para reducir la fuga de clientes.



## 📋 Descripción del Proyecto

El proyecto aborda el problema de la pérdida de suscriptores utilizando técnicas de **Ciencia de Datos**. Se realiza una limpieza profunda de la base de datos, transformación de variables categóricas y un análisis estadístico de los factores que más influyen en que un cliente decida cancelar su servicio.

## 🛠️ Tecnologías y Librerías

* **Python 3.x**
* **Pandas**: Para la manipulación y limpieza de estructuras de datos.
* **Matplotlib / Seaborn**: Para la generación de gráficos y visualización de datos.
* **Jupyter Notebook**: Entorno de desarrollo interactivo.

## 🚀 Etapas del Análisis

1. **Extracción y Carga**: Importación de la base de datos `Base Telecom.csv`.
2. **Limpieza de Datos**: 
   - Eliminación de columnas no informativas (como `ID_Cliente`).
   - Tratamiento de valores nulos y tipos de datos.
3. **Ingeniería de Características (Feature Engineering)**:
   - Aplicación de **One-Hot Encoding** para convertir variables de texto en numéricas.
   - Creación de variables binarias (0 y 1) para facilitar el procesamiento.
4. **Visualización de la Tasa de Abandono**: Creación de gráficos para entender la proporción de clientes que se quedan vs. los que se van.


## 📊 Hallazgos Principales

Tras el análisis, se identificaron los siguientes puntos críticos:
* **Tasa de Abandono**: Aproximadamente el **26.54%** de la base de clientes ha cancelado el servicio.
* **Factor de Riesgo (Fibra Óptica)**: Es el servicio con mayor correlación con el abandono, sugiriendo posibles problemas de precio o calidad técnica.
* **Métodos de Pago**: Los clientes con "Cheque Electrónico" tienen una tendencia significativamente mayor a abandonar comparado con los pagos automáticos.
* **Antigüedad**: El primer año es el más crítico; si un cliente supera los 12 meses, la probabilidad de fuga disminuye drásticamente.

<img width="1390" height="1117" alt="image" src="https://github.com/user-attachments/assets/8f391485-4b7b-4524-9f30-4e52ba9bb389" />


## 💡 Estrategias de Retención Propuestas

Basado en los datos, se recomiendan las siguientes acciones:

* **Auditoría de Servicio**: Revisar la infraestructura de Fibra Óptica para mejorar la satisfacción del cliente.
* **Incentivos de Automatización**: Ofrecer beneficios a los clientes que migren de pagos manuales a **Pagos Automáticos**.
* **Programa de Bienvenida**: Implementar un seguimiento proactivo durante el primer año (periodo de mayor riesgo).
* **Migración de Contratos**: Incentivar el paso de contratos mensuales a anuales para aumentar la lealtad.

