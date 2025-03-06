# Entrenamiento de una Red Neuronal con Keras y MNIST

## Descripción
Este proyecto implementa una red neuronal artificial (ANN) utilizando Keras para el reconocimiento de dígitos escritos a mano de la base de datos MNIST. La red neuronal es un modelo secuencial con una capa de entrada, una capa oculta con activación ReLU y una capa de salida con activación softmax.

## Requisitos
Para ejecutar este código, se requieren las siguientes bibliotecas de Python:
- `numpy`
- `keras`
- `matplotlib`

Puedes instalarlas utilizando el siguiente comando:
```bash
pip install numpy tensorflow matplotlib
```

## Estructura del Código
1. **Carga de datos:** Se obtiene el conjunto de datos MNIST, que contiene imágenes de dígitos escritos a mano.
2. **Preprocesamiento:** Se normalizan los datos y se convierten las etiquetas a formato one-hot encoding.
3. **Definición del modelo:** Se crea una red neuronal con una capa oculta de 512 neuronas y activación ReLU.
4. **Compilación del modelo:** Se usa el optimizador RMSprop y la función de pérdida categorical crossentropy.
5. **Entrenamiento:** Se entrena la red neuronal en 8 épocas con un tamaño de batch de 128.
6. **Evaluación:** Se mide la precisión del modelo en el conjunto de prueba y se muestra en pantalla.

## Ejecución
Para entrenar y evaluar el modelo, ejecuta el siguiente comando en la terminal:
```bash
python main.py
```

## Salida Esperada
Después del entrenamiento, el modelo imprimirá la precisión obtenida en el conjunto de prueba, indicando qué tan bien reconoce los dígitos escritos a mano.

## Notas
- Puedes modificar la arquitectura de la red neuronal ajustando el número de capas y neuronas en el código.
- Ajustar los hiperparámetros como la cantidad de épocas o el tamaño del batch puede mejorar la precisión del modelo.
- Si deseas visualizar ejemplos de predicciones, puedes agregar código para mostrar imágenes junto con las clasificaciones realizadas por la red neuronal.

---
