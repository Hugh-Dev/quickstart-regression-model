# Linear Regression

Los modelos de regresión son como 'calculadoras inteligentes' que usan datos pasados para predecir números.
Por ejemplo, si tienes datos de tamaños de casas y sus precios, la regresión aprende a estimar el precio de
una casa nueva basándose en su tamaño.

## ¿Qué es la Regresión Lineal?

La **regresión lineal** es el modelo de *machine learning* más básico y fundamental dentro de los algoritmos de regresión. Su objetivo es **encontrar una relación lineal** (en forma de línea recta o hiperplano) entre una o más variables independientes (**features**, \(X\)) y una variable dependiente continua (**target**, \(y\)).  

## Fórmula Matemática

La ecuación general de la regresión lineal simple (con una sola variable \(x\)) es:  

$$
y = \beta_0 + \beta_1 x + \epsilon
$$  

- **\(y\)**: Valor a predecir (ej: precio de una casa).  
- **\(x\)**: Variable predictora (ej: metros cuadrados).  
- **\(\beta_0\)**: Intercepto (valor de \(y\) cuando \(x = 0\)).  
- **\(\beta_1\)**: Pendiente (cambio en \(y\) por unidad de \(x\)).  
- **\(\epsilon\)**: Error (diferencia entre el valor real y la predicción).  

**En regresión lineal múltiple** (varias variables):  
$$
y = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + ... + \beta_n x_n + \epsilon
$$

## ¿Cómo Funciona?  

**Entrenamiento**:  

- El algoritmo ajusta \(\beta_0\) y \(\beta_1\) para minimizar el **error cuadrático medio (MSE)** entre las predicciones y los valores reales.  
- Métodos comunes: **Mínimos cuadrados ordinarios (OLS)** o **gradiente descendente**.  

**Predicción**:  

- Usa la ecuación aprendida para estimar \(y\) con nuevos valores de \(x\).  
