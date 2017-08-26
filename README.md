# hnh17-datascience
The repository for the data science track at HnH17

### Toolchain setup
To install the necessary toolchain follow these steps:
1. Install Python 3.6 from python.org
2. Install miniconda from https://conda.io/miniconda.html
3. Open a command prompt
4. Add the conda forge channel:
```
conda config --add channels conda-forge
```
5. Create a new conda environment called "machinelearn" with python 3.5
```
conda create --name machinelearn python=3.5 jupyter scikit-learn pandas matplotlib tensorflow keras
```
6. activate the new environment
```
activate machinelearn
```
7. Change the backend to Tensorflow in keras.json:
C:\Users\???\.keras\keras.json
