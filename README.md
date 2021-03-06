# hnh17-datascience

:warning: **REPOSITORY NOT ACTIVE SINCE 2017 Dependabot alerts in git security settings disabled**

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
5. Change the backend to Tensorflow (Windows - nb Mac users may not need this step):
```
Navigate to %LOCALAPPDATA%\Continuum\Anaconda3\envs\machinelearn\etc\conda\activate.d
edit the batch file. Replace "theano" with "tensorflow"
```
6. activate the new environment
```
activate machinelearn
```
7. start the Jupyter interactive notebook
```
juypter notebook
```
