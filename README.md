# Detección de Personajes de Los Simpsons con Redes Convolusionales

Este proyecto utiliza una red neuronal convolucional para identificar personajes de la serie **Los Simpsons** a partir de imágenes. El objetivo principal es entrenar un modelo capaz de clasificar correctamente a los personajes presentes en un video.

## Contenido

- `simpsons.ipynb`: Notebook principal que incluye la carga de datos, preprocesamiento, construcción del modelo, entrenamiento, evaluación y predicción.
- `data/`: Directorio esperado para almacenar las imágenes organizadas por carpetas según el personaje.

## Requisitos

Asegúrate de tener instaladas las siguientes dependencias:

- Python 3.8+
- TensorFlow >= 2.x
- NumPy
- Matplotlib
- scikit-learn
- pandas

Puedes instalar los requisitos usando:

```bash
pip install -r requirements.txt
````
## Estructura esperada de los datos

Se espera que las imágenes estén organizadas de la siguiente manera:

```
data/
├── bart_simpson/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── homer_simpson/
│   ├── image1.jpg
│   └── ...
├── lisa_simpson/
│   └── ...
└── ...
```

Cada subcarpeta representa una clase (un personaje diferente).

## Ejecución

Abre y ejecuta el notebook en un entorno Jupyter:

```bash
jupyter notebook simpsons.ipynb
```

A lo largo del notebook se realiza lo siguiente:

1. Carga y preprocesamiento de datos.
2. Definición de un modelo CNN para clasificación de imágenes.
3. Entrenamiento del modelo.
4. Evaluación del desempeño.
5. Predicciones de prueba con imágenes nuevas.

## Resultados

El modelo alcanza una precisión competitiva en la clasificación de los personajes, con métricas como accuracy y matrices de confusión para evaluar el desempeño.

## Contribuciones

Si deseas mejorar este proyecto o agregar nuevos personajes, puedes hacerlo agregando nuevas carpetas con imágenes al directorio `data/` y reentrenando el modelo.

---


