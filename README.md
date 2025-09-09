# TFM — House Prices Prediction

Repositorio del TFM para predicción de precios de viviendas.  
Incluye un entorno de Conda reproducible con todas las librerías necesarias para un flujo de *Machine Learning* de inicio a fin (carga de datos, EDA, modelado, explicabilidad y notebooks).

---

## Requisitos

- **Anaconda** o **Miniconda** (Windows 10/11).
- (Opcional) **mamba** para instalaciones más rápidas.

Instalar mamba (opcional):

    conda install -n base -c conda-forge -y mamba


1.  **Clonar el repositorio:**

    git clone [https://github.com/Ruben-SM-01/TFM-House-Prices-Prediction.git](https://github.com/Ruben-SM-01/TFM-House-Prices-Prediction.git)
    cd TFM-House-Prices-Prediction

2.   **Prioridad de canales**

    Para evitar conflictos de dependencias:

    conda config --set channel_priority strict

3.  **Crear el entorno de Conda desde el archivo:**

    mamba env create -f environment.yml


4.  **Activar el nuevo entorno:**

    conda activate ENVTFM


5.  **Registrar el entorno en Jupyter (opcional pero recomendado):**
    Este comando hace que "Python (ENVTFM)" aparezca como una opción de kernel en Jupyter.

    python -m ipykernel install --user --name ENVTFM --display-name "Python (ENVTFM)"


6.  **Iniciar Jupyter Notebook:**

    jupyter notebook


NOTA: Si mamba no esta instalado, realizar: 
conda install -n base -c conda-forge -y mamba