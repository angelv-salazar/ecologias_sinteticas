# ecologias_sinteticas

Estos son cuadernos colaborativos utilizando StyleGAN2 para generar imágenes:
- **a_preparar-dataset.ipynb**: Es para preparar el conjunto de datos, recortar el centro y convertir las imágenes en cuadradas de tamaño 512x512 o 1024x1204. También verifica las imágenes.
- **b._StyleGAN2_entrenamiento_modelo.ipynb**: Es para entrenar un modelo de aprendizaje automático utilizando StyleGAN2 basado en transferencia de aprendizaje. Es mejor comenzar usando imágenes con un tamaño de 512 px.
- **c._StyleGAN2_generador.ipynb**: Genera imágenes a partir del modelo entrenado y puedes usarlas para crear un video generando fotogramas entre imágenes.
- **d._nube_de_puntos.ipynb**: Genera un archivo ply de nube de puntos a partir de la carpeta de frames de las interpolaciones
