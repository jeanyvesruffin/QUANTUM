# QUANTUM with IBM

## Environnement de travail


Telecharger:

* [python](https://www.python.org/)
* [anaconda](https://www.anaconda.com/products/individual)

*Toutes les commandes executees seront dans Anaconda Prompt*


Installation de qiskit et jupyter (IDE online)

```cmd
pip install qiskit
conda install -c conda-forge jupyterlab
```


```cmd
cd My_projet
// Commande pour demarrer le server virtuel jupyter
My_projet:jupyter notebook

```
Une fois le serveur virtuel demarre, nous pouvons y ajouter python3 comme notebook.

ex: http://localhost:8888/tree


## Configuration du projet

Version python utilise

```cmd
(base) D:\PROGRAMMING\QUANTUM\QUANTUM\First_projet>python --version
Python 3.8.3
```


Execute le python installe sur la machine

```cmd
(base) D:\PROGRAMMING\QUANTUM\QUANTUM\First_projet>python
Python 3.8.3 (default, Jul  2 2020, 17:30:36) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>

```

Quitter python

```cmd
CTRL+Z
```

Exemple pour installer environnement python 2.7

```cmd
(base) D:\PROGRAMMING\QUANTUM\QUANTUM\First_projet>conda create -n py27 python=2.7
Collecting package metadata (current_repodata.json): done
Solving environment: failed with repodata from current_repodata.json, will retry with next repodata source.
Collecting package metadata (repodata.json): done
Solving environment: done
## Package Plan ##

  environment location: C:\Users\admin\anaconda3\envs\py27

  added / updated specs:
    - python=2.7
#
# To activate this environment, use
#
#     $ conda activate py27
#
# To deactivate an active environment, use
#
#     $ conda deactivate

```

Activer anaconda avec python27

```cmd
conda activate py27

(py27) D:\PROGRAMMING\QUANTUM\QUANTUM\First_projet>
```

Installer notebook ipykernel avec conda

```cmd
(py27) D:\PROGRAMMING\QUANTUM\QUANTUM\First_projet>conda install notebook ipykernel


```

Autre methode, permet de mettre a jour votre environnement


```cmd

conda update --name base conda

```

Pour connaitre le contenu des package install

````cmd
(py27) D:\PROGRAMMING\QUANTUM\QUANTUM\First_projet>conda list --name base conda

# packages in environment at C:\Users\admin\anaconda3:
#
# Name                    Version                   Build  Channel
anaconda                  2020.07                  py38_0
anaconda-client           1.7.2                    py38_0
anaconda-navigator        1.9.12                   py38_0
anaconda-project          0.8.4                      py_0
conda                     4.9.1            py38haa95532_0
conda-build               3.18.11                  py38_1
conda-env                 2.6.0                         1
conda-package-handling    1.7.2            py38h76e460a_0
conda-verify              3.4.2                      py_1
msys2-conda-epoch         20160418                      1
```





