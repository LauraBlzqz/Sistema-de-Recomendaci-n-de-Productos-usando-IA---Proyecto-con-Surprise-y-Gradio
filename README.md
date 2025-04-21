# Sistema de Recomendación de Productos con IA

Este proyecto implementa un sistema de recomendación de productos utilizando inteligencia artificial. Se ha usado el algoritmo SVD (Singular Value Decomposition) de la librería **Surprise** para predecir las valoraciones de productos e interactuar con una interfaz sencilla y atractiva utilizando **Gradio**.

## Requisitos

- Python 3.x
- pandas
- numpy
- gradio
- surprise

## Instalación

Para instalar las dependencias necesarias, ejecuta el siguiente comando:
pip install -r requirements.txt

Uso
Para ejecutar el sistema de recomendación, utiliza el siguiente código:
python app.py


Luego, podrás interactuar con la interfaz de usuario en tu navegador. Solo tienes que introducir tu ID de usuario para recibir recomendaciones personalizadas.

Funcionamiento
1.El sistema predice la valoración de productos basándose en las valoraciones previas de los usuarios.

2.Utiliza un modelo SVD de la librería Surprise para la predicción.

3.La interfaz de usuario es desarrollada con Gradio, permitiendo una experiencia de uso interactiva y visual.

Contribuciones
¡Las contribuciones son bienvenidas! Si tienes alguna mejora o corrección, siéntete libre de hacer un fork del repositorio y enviar un pull request.
