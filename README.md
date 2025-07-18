# Caracterización Estadística de Pacientes con Daño Renal

Este notebook contiene el análisis exploratorio y comparativo de un dataset de pacientes con y sin daño renal, cumpliendo los requisitos de la Tarea 2 de Caracterización Estadística.

## 📂 Contenido

- **Descripción univariada**
  - Media, DE, mediana, IQR para variables continuas.
  - Frecuencias absolutas y relativas para variables categóricas.

- **Matriz de correlaciones**
  - Pearson y Spearman según normalidad.
  - Visualización en heatmap con coeficientes y p-values ajustados.

- **Pruebas de significancia**
  - t-test o Mann-Whitney para dos grupos.
  - ANOVA o Kruskal-Wallis para ≥3 grupos.
  - Chi-cuadrado o Fisher exacta para categóricas.

- **Gráficos**
  - Boxplots y gráficos de barras para asociaciones significativas.

## 🛠️ Librerías utilizadas

- pandas
- numpy
- matplotlib
- seaborn
- scipy

## 📊 Dataset

El dataset fue proporcionado por el profesor en clase, e incluye variables clínicas como creatinina, eGFR, presión arterial, BMI, sexo, tabaquismo, diabetes y clasificación de daño renal.

## ✅ Uso

1. Clona este repositorio.
2. Instala las dependencias:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
