## Taller realizado en PyConAR 2018

# Data: Usamos la imagen Landsat8
La pueden encontrar en al Drive: https://drive.google.com/drive/folders/1oXZJR4rHiAJO4yJnyx8xuAw1XgfOrOmd 

-----------------------------------------------------------------------------------------------

# Requisitos:

Python 3.7

GDAL==2.3.0
jupyter==1.0.0
scikit-image==0.14.1
scikit-learn==0.20.0
scipy==1.1.0
seaborn==0.9.0
numpy==1.15.3
pandas==0.23.4

Ademas utilizamos la libreria roipoly.py :  https://github.com/jdoepfert/roipoly.py



---------------------------------------------------------------------
En el marco del taller me parecia que estaba bueno crear un enviroment con conda pero no es necesario que sea realice ni con enviroments ni con conda.


Opcion conda enviroments:
1. Creamos un ambiente en conda llamado pycon_test:

conda create -n pycon_test python=3.7.1 anaconda

2. Ingresamos al ambiente:

source activate pycon_test

3. Instalamos las siguientes librerias:

conda install gdal
conda install glob
conda install jupyter
conda install -c conda-forge scikit-image
conda install -c anaconda scikit-learn
conda install pandas
conda install seaborn
conda install numpy

4. Salimos del ambiente:
source deactivate


