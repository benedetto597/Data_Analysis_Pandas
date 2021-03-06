<div align="center">
    
<!-- Encabezado -->
## Data Analysis with Pandas and Python

## Sección 1 - Installation and Setup
### 21/12/2021 - 23/12/2021

</div>

_______

#### 1. Introduction to Data Analysis with Pandas and Python

1. Instalar Anaconda para Linux
    * [Linuxsize](https://linuxize.com/post/how-to-install-anaconda-on-ubuntu-20-04/)
<br>

#### 7. Create conda Environment and Install pandas and Install Pandas & Jupyter Notebook
1. Crear un entorno de desarrollo con Anaconda
    ```
    conda create --name <nombreAmbiente>
    ```
1. Activar y desactivar un entorno de desarrollo con Anaconda
    ```
    conda activate <nombreAmbiente>
    conda deactivate <nombreAmbiente>
    ```
1. Información de todos los ambientes de desarrollo con Anaconda
    ```
    conda info --envs
    ```
1. Instalar bibliotecas para optimizar la ejecución del código
    ```
    conda install bottleneck numexpr
    ```
1. Actualizar todos los paquetes instalados por Anaconda
    ```
    conda update --all
    ```
1. Eliminar un entorno virtual de Anaconda 
    ```
    conda deactivate
    conda remove --name <nombreAmbiente> --all
    ```
* Pandas se puede instalar usando **Anaconda** o **Pip**, ambos son gestores de paquetes o bibliotecas.
    ```
    sudo pip3 install pandas
    ``` 

#### 16. Popular Keyboard Shortcuts in Jupyter Notebook

* **H** --> Help: Abre una ventana emergente con todos los shortcuts disponibles

* **B** --> Below: Crear una celda abajo de la celda actual

* **Esc** --> Escape: Salir del modo escritura de una celda pero mantenerla seleccionada

* **A** --> Above: Crear una celda encima de la celda actual

* **DD** --> Delete: Eliminar la celda seleccionada

#### 17. Import Libraries into Jupyter Notebook

* Importar Pandas en Jupyter Notebook
    ```
    import pandas as pd
    import numpy as np
    ```

* Ver la versión de Pandas en Jupyter Notebook 
    ```
    pd.__version__
    ```
#### 18. Troubleshooting Issues with Jupyter Notebook

* Permitir a los Jupyter Notebook autocompletar con Tab
    * Ejecutar en una celda para desactivar la libreria Jedi
        ```
        %config Completer.use_jedi = False
        ```


_______

### Autores 
| Nombre | Contacto |
|:-------------:| :-----:|
| Edgar Benedetto | [Gmail](mailto:ejbg597@gmail.com) |
