# ⏳ Predicción de Series Temporales

Este proyecto muestra un ejemplo de **análisis y predicción de series temporales** utilizando Python.  
Se utiliza como dataset la clásica serie de pasajeros aéreos (`AirPassengers`) para ilustrar el flujo completo de un análisis predictivo.

## 📑 Contenido
1. **Carga de datos** → Importación y limpieza de la serie temporal.
2. **Análisis Exploratorio (EDA)** → Visualización de tendencia, estacionalidad y ruido.
3. **Modelos de predicción** → 
   - Holt-Winters (suavizamiento exponencial).
   - ARIMA.
4. **Evaluación** → Comparación de modelos con métricas (MAE, RMSE).
5. **Visualización** → Gráficas comparativas de valores reales vs. predicciones.
6. **Conclusiones** → Reflexiones sobre los resultados obtenidos.

## 🛠️ Tecnologías
- Python 3.x
- Pandas
- Numpy
- Matplotlib / Seaborn
- Statsmodels
- Scikit-learn

## 📦 Instalación
Clona el repositorio y entra en la carpeta:
```bash
git clone https://github.com/TU_USUARIO/TimeSeries-Prediction.git
cd TimeSeries-Prediction
```

Instala las dependencias:
```bash
pip install -r requirements.txt
```

## ▶️ Ejecución
Abre el notebook:
```bash
jupyter notebook notebook.ipynb
```

## 📊 Resultados
- Holt-Winters logra capturar mejor la estacionalidad de la serie.
- ARIMA también ofrece predicciones sólidas, pero requiere ajuste de hiperparámetros.
- Se demostró el flujo completo: **EDA → Modelado → Evaluación → Conclusiones**.

## ✨ Autor
Proyecto desarrollado por **[Natalia Beltran]**  
Portafolio en GitHub: [https://github.com/xxnathyxx/TimeSeries-Prediction/tree/main](https://github.com/xxnathyxx)
