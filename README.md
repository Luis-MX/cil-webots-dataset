# Dataset CIL Webots limpio

Este dataset fue generado a partir de:

https://github.com/Luis-MX/cil-webots-dataset.git

Se eliminaron rangos anómalos de `frame_id` detectados durante la auditoría visual, aplicando la eliminación a todos los comandos.

## Rangos eliminados

[(9015, 9382), (23540, 23870), (39430, 39480)]

## Conteo

- Registros originales: 15429
- Registros eliminados: 679
- Registros limpios: 14750
- Imágenes únicas referenciadas: 14750

## Estructura

```text
driving_log.csv
README.md
images/
```

El archivo `driving_log.csv` conserva la estructura esperada por la libreta de entrenamiento.
