# hnh17-datascience
The repository for the data science track at HnH17

### Toolchain setup
To install the necessary toolchain follow these steps:
1. Install miniconda from https://conda.io/miniconda.html
2. Open a command prompt
3. Add the conda forge channel:
```
conda config --add channels conda-forge
```
4. Create a new conda environment called "machinelearn" with python 3.5
```
conda create --name machinelearn python=3.5 jupyter scikit-learn pandas matplotlib tensorflow keras
```
5. activate the new environment
```
activate machinelearn
```
6. Change the backend to Tensorflow in keras.json:
C:\Users\???\.keras\keras.json
