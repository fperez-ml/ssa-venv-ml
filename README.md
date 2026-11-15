# ssa-venv-ml

Este repositorio es un ejemplo prático para generar un entorno virtual con las librerías mas utilziadas en el ámbito del Aprendizaje Automático (Machine Learning) que se detallan a continuación:

| Librería | Descripción |
|-----------|-------------|
| **NumPy** | Cálculo científico |
| **Pandas** | Análisis y manipulación de *datasets* |
| **Matplotlib** | Gráficos |
| **Seaborn** | Visualización de datos estadísticos |
| **Scikit-Learn** | Machine Learning |
| **TensorFlow** | Machine Learning, especialmente para redes neuronales y *Deep Learning* |
| **Keras** | Redes neuronales y *Deep Learning*. Es una API de alto nivel que suele usar TensorFlow como *backend* para operaciones de bajo nivel. También puede utilizar otros *backends*, como por ejemplo PyTorch. |
| **PyTorch** | Framework de código abierto que admite una amplia variedad de arquitecturas de red neuronal, desde algotimos de regresión lineal simple hasta redes reuronales convolucionales complejas y modelos de transformadores generativos utilizados para el procesamiento de imágenes y del lenguaje |

Estas librerías se incluiran en los diversos ficheros requirements.txt para la generación de entornos donde se pueda aplicar los modelos ML adecuados para el problema a resolver.

## Creación de un Entorno Virtual

Para la generación de un entorno virtual basado en un fichero requirements.txt ejecutaremos el siguiente comando

```bash
python -m venv venv
# Por simplicidad no se incluye la actividad del entorno en cada Sistema Operativo
# Una vez activado el entorno según el sistema operativo
pip install -r requirements-basico.txt
```


