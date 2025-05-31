# 🏡 Predicción de Precios de Viviendas

Este proyecto consiste en predecir el precio de viviendas usando el conjunto de datos de **Ames Housing**, como parte de una competencia estilo Kaggle. Se utilizaron técnicas de preprocesamiento, ingeniería de características, selección de modelos y ajuste de hiperparámetros.

![Feature Importance](feature_importance.png)

---

## 📁 Estructura del Proyecto

- `train.csv`: Datos de entrenamiento con el precio (`SalePrice`)
- `test.csv`: Datos para predicción final
- `notebook.ipynb`: Análisis completo y modelo
- `requirements.txt`: Dependencias del entorno
- `feature_importance.png`: Visualización de las características más importantes

---

## ⚙️ Tecnologías utilizadas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- RandomForest, Ridge, Lasso, DecisionTree
- Pipelines y ColumnTransformer

---

## 🚀 Cómo ejecutar el proyecto

1. **Clona el repositorio**:

```bash
git clone https://github.com/Lemus2901/Price-housing.git
cd Price-housing
````

2. **Crea un entorno virtual (opcional pero recomendado)**:

```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

3. **Instala las dependencias**:

```bash
pip install -r requirements.txt
```

4. **Ejecuta el notebook**:

Abre el archivo `notebook.ipynb` en Jupyter Notebook o VS Code y sigue los pasos.

---

## 📊 Resultados

Se probaron varios modelos, y el mejor desempeño se logró con **Random Forest** ajustado con `RandomizedSearchCV`. El RMSE promedio fue de aproximadamente **31025.83** en validación cruzada.

## Precio real vs precio predicho
![Comparacion precio real vs precio predicho](img.png)


---

## 🧠 Autor

**Andrés Felipe Lemus Victoria**

Estudiante de Ingeniería de Sistemas, entusiasta de la ciencia de datos y la inteligencia artificial.

---

## 🌐 Repositorio

[🔗 GitHub - Lemus2901/Price-housing](https://github.com/Lemus2901/Price-housing)
*[Andres Felipe Lemus V](https://www.linkedin.com/in/andres-felipe-lemus-v-7943882a9/)*

