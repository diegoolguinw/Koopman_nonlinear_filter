# Algoritmo de filtraje no lineal basado en operador de Koopman, aplicado a modelos en epidemiología

## Departamento de Ingeniería Matemática, Universidad de Chile

### Tesis para optar al grado de Magíster en Ciencias de la Ingeniería, Mención Matemáticas Aplicadas.
### Memoria para optar al título de Ingeniero Civil Matemático.

**Autor: Diego Olguín Wende.**

**Profesor guía: Héctor Ramírez.**

**Profesor co-guía: Axel Osses.**

**Comisión:**

* **Joaquín Fontobona Torres (Presidente).**
* **Gonzalo Ruz Heredia.**
* **Benjamín Herrmann Priesnitz.**

Este repositorio contiene el código y los notebooks utilizados en esta tesis. A continuación, se describen los diferentes archivos y notebooks, así como las dependencias necesarias para ejecutar el proyecto.

## Capítulos

* Capítulo 1: Introducción.
* Capítulo 2: Preliminares.
* Capítulo 3: Kernel Extended Dynamic Mode Decomposition [[**Notebook**](notebooks/chapter3.ipynb)].
* Capítulo 4: Algoritmo de filtraje no lineal en tiempo discreto y estimación de parámetros [[**Notebook 1**](notebooks/chapter4_1.ipynb)] [[**Notebook 2**](notebooks/chapter4_2.ipynb)] [[**Notebook 3**](notebooks/chapter4_3.ipynb)].
* Capítulo 5: Discusiones, conclusiones y trabajo futuro.

## Dependencias

Para ejecutar el código de este repositorio, se necesita tener instaladas las siguientes bibliotecas de Python:

- Numpy
- Matplotlib
- Seaborn
- Scipy
- Pandas
- Plotly
- Kaleido
- Sklearn
- kkf
- tqdm
- PyMC
- nbformat

Se puede instalar todas las dependencias utilizando Anaconda:

```sh
conda create -c conda-forge -n kerkkf_env "pymc>=5"
conda activate kerkkf_env
conda install pip
pip install numpy matplotlib seaborn scipy pandas plotly kaleido sklearn kkf tqdm nbformat
