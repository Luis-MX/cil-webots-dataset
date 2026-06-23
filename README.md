# Dataset CIL Webots

Dataset balanceado para entrenamiento de Conditional Imitation Learning (CIL)
en Webots.

## Contenido

- `driving_log.csv`: archivo con rutas de imágenes, comando de navegación y ángulo de dirección.
- `images/`: imágenes capturadas desde la cámara del vehículo.

## Columnas principales

- `image_path`: ruta relativa de la imagen.
- `navigation_command`: comando CIL codificado numéricamente.
- `command_name`: nombre del comando.
- `steering_angle`: ángulo de dirección usado como etiqueta.
- `camera_name`: cámara de origen, si está disponible.
- `source`: identificador de origen del dataset.
- `original_image_path`: ruta original antes de crear este dataset balanceado.

## Comandos

- 2 = FOLLOW_LANE
- 3 = LEFT
- 4 = RIGHT
- 5 = STRAIGHT

## Resumen

Total de muestras: 15429

Distribución por comando:

- FOLLOW_LANE: 8000
- LEFT: 3550
- RIGHT: 2370
- STRAIGHT: 1509


## Origen

Este dataset fue creado a partir de:

`dataset_cil/driving_log.csv`

El objetivo de este subconjunto es reducir el desbalance del dataset original
y facilitar su uso en Google Colab mediante `git clone`.
