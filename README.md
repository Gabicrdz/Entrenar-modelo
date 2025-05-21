# Predictor de Valores para Función Cuadrática

Este proyecto implementa un modelo de TensorFlow.js que predice los valores de `x` para la función cuadrática `y = 2x² - 3x + 1`.

## Descripción

El código utiliza una red neuronal simple para resolver el problema inverso de una función cuadrática: dado un valor de `y`, encontrar el correspondiente valor (o valores) de `x`.

## Características

- Implementación minimalista con HTML, JavaScript y TensorFlow.js
- Entrenamiento de red neuronal en el navegador
- Capacidad para encontrar ambas soluciones cuando existen (para valores de y ≤ 1.25)
- Verificación de resultados con cálculo de error

## Requisitos

- Navegador web moderno
- Conexión a internet (para cargar TensorFlow.js desde CDN)

## Instrucciones de uso

1. Clonar el repositorio:

```bash
git clone https://github.com/Gabicrdz/Entrenar-modelo.git
```

2. Abrir el archivo `index.html` en un navegador web

3. Usar la aplicación:
   - Haz clic en "Entrenar Modelo"
   - Ingresa un valor de y
   - Haz clic en "Predecir"
   - Revisa los resultados y la verificación

## Cómo funciona

El modelo invierte la relación habitual entre `x` e `y`, entrenando una red neuronal para predecir valores de `x` a partir de valores de `y`. Para casos donde existen dos soluciones posibles, utiliza métodos adicionales para encontrar ambas raíces de la ecuación cuadrática.
