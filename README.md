# Descripción del Proyecto

Este repositorio contiene scripts en formato Jupyter Notebook (`.ipynb`) para la generación y análisis de espectrogramas utilizando técnicas de ventana deslizante y redes neuronales.

## Contenido

1. **Generación de Espectrogramas**
   - **Archivo**: `generacion_espectrogramas.ipynb`
   - **Descripción**: Este script utiliza la técnica de ventana deslizante para generar espectrogramas a partir de señales de audio.
   - **Uso**: Ejecuta este script para obtener espectrogramas que pueden ser utilizados como entrada para redes neuronales.

2. **Red Neuronal Convolucional**
   - **Archivo**: `red_neuronal_convolucional.ipynb`
   - **Descripción**: Este script implementa una red neuronal convolucional (CNN) entrenada con los espectrogramas generados por el script anterior.
   - **Uso**: Ejecuta este script para entrenar y evaluar la red neuronal convolucional con los espectrogramas.

3. **Red Vit Transformers**
   - **Archivo**: `red_vit_transformers.ipynb`
   - **Descripción**: Este script implementa una red Vit Transformers entrenada con los mismos espectrogramas generados por el primer script.
   - **Uso**: Ejecuta este script para entrenar y evaluar la red Vit Transformers con los espectrogramas.

4. **Prueba de Concepto**
   - **Archivo**: `prueba_de_concepto.ipynb`
   - **Descripción**: Este script realiza la amplificación y generación de espectrogramas a través de la ventana deslizante, utilizando una serie de audios generados en una prueba de campo.
   - **Uso**: Ejecuta este script para probar la red neuronal Vit Transformers con los espectrogramas generados a partir de audios de prueba de campo.

## Instrucciones de Uso

1. **Clonar el Repositorio**:
   ```sh
   git clone https://github.com/helbert-novoa/QuindiBIRD
   cd tu-repositorio
