# Clasificación - Bank Marketing Dataset
**Autor:** Cristian Andrés Godoy Angel  
**Versión:** v1.0  

## bjetivo
Evaluar la capacidad de análisis, limpieza, exploración, modelado y evaluación en un dataset real de campañas de marketing bancario.  
Se busca predecir si un cliente se suscribirá a un depósito a plazo fijo, basado en datos históricos.

## 🗂Dataset
- Fuente: UCI Machine Learning Repository  
- Registros: 45.211 clientes  
- Variables: 16 + variable objetivo (`y`)

## Estructura del análisis

### **Preprocesamiento y Limpieza**
- Revisión y eliminación de duplicados ✅  
- Verificación de tipos de datos ✅  
- Análisis de valores "unknown" en variables categóricas ✅  
- Manejo de valores atípicos en variables como `duration` y `campaign` ✅  
- Justificación ética y técnica de cada decisión ✅  

### **Exploración de Datos (EDA)**
- Histogramas de variables numéricas ✅  
- Gráficos de barras para categóricas ✅  
- Boxplots y scatterplots multivariados ✅  
- Mapa de calor de correlación ✅  
- Estadísticas descriptivas con `describe()` ✅  
- Interpretación clara y útil de cada gráfico ✅

### **Modelado Predictivo**
- Implementación de `ColumnTransformer` y `Pipeline` ✅  
- Modelos usados:  
  - Árbol de Decisión  
  - Support Vector Machine (SVM) con `class_weight='balanced'`  
- Evaluación con:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Matriz de confusión  
- Comparación de resultados y elección del mejor modelo ✅  

### **Conclusiones**
- El modelo SVM fue el más efectivo para predecir clientes que **sí** aceptan el producto.  
- Las variables más relevantes fueron `duration`, `poutcome`, `contact` y `campaign`.  
- Se justificaron decisiones éticas y técnicas en todo el proceso.  

## Herramientas utilizadas
- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

## Reproducibilidad
Todos los pasos están documentados y pueden ser ejecutados de principio a fin desde el archivo `.ipynb`.

