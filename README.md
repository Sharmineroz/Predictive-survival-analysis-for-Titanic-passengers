# Predicción de Supervivencia en el Titanic 🚢

Este proyecto fue desarrollado como parte de la asignatura de **Aprendizaje Automático**. Nuestro objetivo fue aplicar técnicas de aprendizaje supervisado para predecir qué pasajeros sobrevivieron al hundimiento del Titanic, utilizando el famoso dataset de [Kaggle](https://www.kaggle.com/competitions/titanic).

## 🔍 Objetivo

Desarrollar un modelo de clasificación que prediga si un pasajero sobrevivió, en función de variables como su edad, sexo, clase del boleto, entre otras características.

---

## 🧪 Análisis Exploratorio de Datos (EDA)

Se realizó un análisis detallado para entender mejor la distribución y relación entre variables:

- Visualización de distribuciones (edad, tarifa, clase, etc.)
- Análisis de valores faltantes
- Impacto de variables categóricas (sexo, clase, embarque) en la supervivencia
- Transformaciones de variables y creación de nuevas features como:
  - Agrupación de títulos en los nombres
  - Agrupación de edad en rangos

---

## 🤖 Modelos Entrenados

Se entrenaron y evaluaron varios modelos de clasificación:

- **Regresión Logística**
- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **XGBoost**

Se utilizaron métricas como *accuracy*, *precision*, *recall* y *f1-score* para evaluar el desempeño de los modelos. También se aplicó validación cruzada para obtener resultados más robustos.

---

## 🧰 Herramientas y Librerías

- Python 3
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Estructura del Repositorio

```
titanic-survival-prediction/
�?├── data/                 # Dataset original (train.csv, test.csv)
├── notebooks/
�?  └── EDA_Titanic.ipynb # Análisis exploratorio y entrenamiento de modelos
├── models/               # Modelos entrenados (opcional)
├── README.md             # Este archivo
└── requirements.txt      # Librerías necesarias
```

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook:
   ```bash
   jupyter notebook notebooks/EDA_Titanic.ipynb
   ```

---

## 📌 Contribuyentes

- Valentina Isaza
- Juan Jos�� Bonilla
- Nelcy Luc��a Zapata
- Ricardo Mu?oz

---

## 📜 Licencia

Este proyecto se distribuye bajo la licencia MIT.
