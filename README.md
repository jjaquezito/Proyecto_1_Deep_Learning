# Proyecto 1: Competencia de Modelación

**CC3092 · Deep Learning y Sistemas Inteligentes** — Universidad del Valle de Guatemala, 2026

Autor: Joel Jaquez (23369)

MLP en PyTorch para predecir `SalePrice` sobre un dataset de viviendas (estilo Ames Housing), evaluado por RMSE contra un dataset de prueba entregado el día de la presentación.

## Estructura del repositorio

```
Proyecto_1/
├── data/
│   └── train.csv          # dataset de entrenamiento
├── notebooks/
│   ├── 01_eda.ipynb        # análisis exploratorio de datos
│   ├── 02_training.ipynb   # preprocesamiento, arquitecturas e iteraciones
│   └── 03_predict.ipynb    # carga del modelo final y predicción sobre el dataset de prueba
├── models/                 # pesos del modelo final + pipeline de preprocesamiento
├── requirements.txt
└── README.md
```

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Cómo reproducir

1. `notebooks/01_eda.ipynb` — exploración y decisiones de preprocesamiento.
2. `notebooks/02_training.ipynb` — entrena las iteraciones y guarda el modelo final en `models/`.
3. `notebooks/03_predict.ipynb` — carga el modelo final y genera predicciones + RMSE sobre un dataset de prueba nuevo.

