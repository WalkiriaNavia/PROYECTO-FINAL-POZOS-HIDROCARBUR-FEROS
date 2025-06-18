# PROYECTO-FINAL-POZOS-HIDROCARBUR-FEROS
ANÁLISIS COMPARATIVO CON MODELOS PREDICTIVOS MACHINE LEARNING MEDIANTE EL MÉTODO PIXLER PARA EVALUAR EL POTENCIAL PRODUCTIVO ENTRE LOS POZOS HIDROCARBURÍFEROS MAYAYA-X1 Y MARGARITA-10

Este proyecto implementa modelos predictivos de Machine Learning para analizar y proyectar el potencial productivo de distintos pozos hidrocarburíferos en Bolivia. Se comparan los yacimientos Mayaya-X1, Margarita-10, Margarita-4 y Lliquimuni-X1 mediante análisis de datos de cromatografía de gases y modelos como Random Forest, RNN y SARIMA.

---

## 📁 ESTRUCTURA DEL PROYECTO

```
CD/
├── 01_BASE_DE_DATOS/
│   ├── GASES_lliquimuniX1.xlsx
│   ├── GASES_margarita10.xlsx
│   ├── GASES_margarita4.xlsx
│   └── GASES_mayayaX1.xlsx
│
├── 02_DESARROLLO_MODELOS/
│   └── PROYECTO_FINAL_ANALISIS_COMPARATIVO_ENTRE_POZOS_HIDROCARBURÍFEROS.ipynb
│
├── 03_DOCUMENTACIÓN/
│   ├── MONOGRAFÍA_WALKIRIA_NAVIA_CIENCIA_DE_DATOS.pdf
│   ├── MONOGRAFÍA_WALKIRIA_NAVIA_CIENCIA_DE_DATOS.docx
│   ├── Carta de aprobación Tutor_Walkira Navia.pdf
│   └── Carta de Aprobación del Tribunal_Walkira Navia.pdf
```

---

## ⚙️ REQUISITOS

- Python 3.10+
- Jupyter Notebook
- Librerías necesarias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn keras tensorflow statsmodels openpyxl
```

---

## ✅ INSTRUCCIONES DE EJECUCIÓN

### 🔧 1. Preparación del entorno

Verificar que Python esté instalado y ejecuta:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn keras tensorflow statsmodels openpyxl
```

---

### 📂 2. Organización de carpetas

Asegúrate de que la estructura esté así:

```
CD/
├── 01_BASE_DE_DATOS/ → contiene archivos .xlsx
├── 02_DESARROLLO_MODELOS/ → contiene el notebook .ipynb
```

---

### 🧠 3. Ejecución del notebook paso a paso

1. Abrir Jupyter Notebook desde terminal o entorno:

```bash
jupyter notebook
```

2. Navegar a:

```
02_DESARROLLO_MODELOS/PROYECTO_FINAL_ANALISIS_COMPARATIVO_ENTRE_POZOS_HIDROCARBURÍFEROS.ipynb
```

3. Ejecutar cada celda en orden. El flujo incluye:

- Carga de datos desde `../01_BASE_DE_DATOS/*.xlsx`
- Limpieza y unificación de los datos
- Gráficos de exploración y Pixler
- Entrenamiento de modelos:
  - Random Forest
  - RNN
  - SARIMA
- Comparación de resultados y métricas (MAE, MSE, precisión)

---

## 📊 RESULTADOS ESPERADOS

- Identificación visual de zonas productivas
- Predicciones por pozo
- Comparación de modelos
- Exportación de gráficos y resultados

---

## 📌 NOTAS

- Las predicciones se basan en profundidad y composición de gases (no en fechas).
- El método gráfico Pixler se emplea como apoyo visual.

---

## 🧑‍💻 AUTORA

- Univ. Walkiria Yuli Navia Barrios  
- Tutor: Ing. Guillermo Lionel Navia Montoya

---

## 📅 FECHA

Junio 2025

---
