# Identificación de Zonas de Sismicidad de Bolivia mediante Aprendizaje No Supervisado

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/drive/u/0/folders/1ulxSIwrUc52hWjI-sed4g1nxenIJ7k6B)
[![Python 3.13](https://img.shields.io/badge/python-3.13-blue.svg)](https://www.python.org/)


Proyecto de investigación orientado a zonificar y caracterizar de forma cuantitativa y reproducible la sismicidad del territorio boliviano utilizando exclusivamente la distribución tridimensional de eventos históricos (**latitud, longitud y profundidad**), aplicando un enfoque de validación consensual entre los algoritmos **K-Means** y **Ward**, estructurado bajo la metodología **CRISP-DM**.

---

## 🚀 Ejecución Rápida en Google Colab

Puedes ejecutar todo el pipeline analítico y generar los resultados de forma automática en tu navegador haciendo clic en el siguiente enlace:

👉 **[Abrir la documentacion completa en google colab](https://drive.google.com/drive/u/0/folders/1ulxSIwrUc52hWjI-sed4g1nxenIJ7k6B)**

👉 **[Abrir cuaderno o notebook en Google Colab](https://drive.google.com/file/d/1Qr-JF2J4z-QGy4_FF2EV9Ub8Wyr6Ttxv/view?usp=drive_link)**

Una vez abierto en Colab, ve al menú superior y selecciona:
`Entorno de ejecución` ➔ `Ejecutar todo`

---

## 📂 Estructura del Repositorio

El repositorio se organiza de la siguiente manera:

```text
├── CODIGOS/
│   ├── notebook_completo.ipynb                             # Cuaderno principal de Jupyter con todo el pipeline
│   ├── notebook_caso1_1900_2026_toda_magnitud.ipynb        # Cuaderno de sensibilidad (Caso 1)
│   └── notebook_caso2_1973_2026_toda_magnitud.ipynb        # Cuaderno de sensibilidad (Caso 2)
├── DATOS/
│   └── FUENTE_USGS/
│       ├── catalogo_crudo_usgs.csv                         # Catálogo sísmico regional original (1900-2026)
│       └── catalogo_bolivia_estricto.csv                   # Catálogo nacional filtrado dentro de los límites de Bolivia
├── DOCUMENTO/
│   └── monografia.pdf                                      # Documento final de la monografía en PDF
├── RESULTADOS/
│   ├── FIGURAS/                                            # Gráficos del modelo en alta resolución (PNG, 300 dpi)
│   ├── TABLAS/                                             # Tablas exportadas en formato LaTeX
│   └── ZIP/
│       └── resultados.zip                                  # Paquete integral comprimido con todos los entregables
└── README.md                                               # Archivo de descripción y guía del repositorio