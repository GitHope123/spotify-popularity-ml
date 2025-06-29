# 🎧 Spotify Popularity Predictor

Proyecto de *machine learning* para **predecir la popularidad de canciones en Spotify** usando características extraídas y procesadas de datasets de Kaggle.

---

## 📋 Descripción

Este repositorio implementa modelos de regresión para predecir la **popularidad** de una canción en **Spotify**, utilizando variables como:

- 🎼 Acousticness
- 💃 Danceability
- ⚡ Energy
- 🎻 Instrumentalness
- 🎤 Liveness
- ⏱️ Tempo
- ⏳ Duration
- 🌟 Artist popularity
- 👥 Followers
- ...y más

El objetivo es construir un modelo robusto que ayude a entender qué factores influyen en el éxito de una canción.

---

## 🧠 Algoritmos Utilizados

- 🌳 `RandomForestRegressor` (modelo principal)
- 📈 `LinearRegression`
- 🚀 `GradientBoosting`
- 🏆 `XGBoost` (opcional)
- 🎲 `RandomizedSearchCV` para optimización de hiperparámetros

---

## 🗂️ Estructura del Proyecto

```bash
spotify-popularity-ml/
├── data/                  # Datos crudos y procesados
├── notebooks/             # Jupyter Notebooks para exploración y modelado
│   └── 01_modelo_base.ipynb
├── src/                   # Scripts fuente (entrenamiento, preprocesamiento)
│   ├── train_model.py
│   └── utils.py
├── outputs/               # Gráficos, métricas y resultados exportados
├── requirements.txt       # Librerías necesarias
├── .gitignore             # Archivos a excluir del control de versiones
└── README.md              # Este archivo
```

---

## 🚀 Cómo empezar

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/spotify-popularity-ml.git
   cd spotify-popularity-ml
   ```

2. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Explora los notebooks** en la carpeta `notebooks/` para ver el análisis exploratorio y los primeros modelos.

4. **Ejecuta los scripts** de entrenamiento desde la carpeta `src/`.

---

## 📊 Resultados

- Se evaluaron varios modelos de regresión.
- El mejor desempeño se obtuvo con `RandomForestRegressor` tras optimización de hiperparámetros.
- Las métricas y gráficos generados se encuentran en la carpeta `outputs/`.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Por favor, abre un *issue* o envía un *pull request* para sugerencias o mejoras.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE`
