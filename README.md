# EMAIL DETECTOR

[![Python](https://img.shields.io/badge/Python-V3.10+-%233776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://www.python.org/downloads/release/python-31014/)
[![Aznaconda](https://img.shields.io/badge/Anaconda-V2.6+-%2344A833?style=for-the-badge&logo=anaconda&logoColor=white&labelColor=101010)](https://www.anaconda.com/docs/getting-started/getting-started)
[![Jupyter](https://img.shields.io/badge/jupyter%20notebook-V7.3+-%23F37626?style=for-the-badge&logo=jupyter&logoColor=white&labelColor=101010)](https://jupyter-notebook.readthedocs.io/en/latest/notebook.html)
[![Numpy](https://img.shields.io/badge/Numpy-V2.2+-%23013243?style=for-the-badge&logo=numpy&logoColor=white&labelColor=101010)](https://numpy.org/install/)
[![Pandas](https://img.shields.io/badge/Pandas-V2.2+-%23150458?style=for-the-badge&logo=pandas&logoColor=white&labelColor=101010)](https://pandas.pydata.org/docs/getting_started/install.html)
[![Scikit-learn](https://img.shields.io/badge/Scikit%20learn-V1.6+-%23F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white&labelColor=101010)](https://scikit-learn.org/stable/install.html)

**Machine Learning application - from exploring essential libraries to performing efficient data ingestion.**

![index](./src/portada.jpg)

> [!WARNING]
> This is not a software or web

## Features

* **Manual introduction** with a real-world Excel example
* **Introduction to Python** - libraries commonly used in data science
* **Basic mathematical** models for analysis and prediction
* **Expository documentation** for each concept
* **Hands-on practices** applying the presented models

## 🛠️ Technologies Used

### GUI

* **Anaconda Navigator 2.6+** – Environment configuration and workspace management

### UI / CLI

* **Terminal** – Installation of libraries and packages
* **Python3** - Code development.
* **Jupyter Notebook** – Code development and documentation

### Libraries

* **NumPy** – Mathematical operations and data structures
* **Pandas** – Data manipulation and analysis
* **Matplotlib** – Data visualization
* **Scikit-learn** – Training of classic ML models and clustering

## 📦 Installation and Configuration

### Requirements

* Python 3.10+ (stable version)
* Linux operating system (any distribution, recommended)
* Virtual environment in Anaconda Navigator

### 1. Clone the repository

```bash
git clone https://github.com/TerrazasJr316/e.git
cd linear-forecasting
```

### 2. Launch the virtual environment

```bash
# to create
~$ conda create -n environment_name python=version anaconda
# to activate
~$ source activate environment_name
# to desactivate
~$ conda deactivate
```

[Managing Environment](https://www.anaconda.com/docs/tools/anaconda-navigator/tutorials/manage-environments)

### 3. Install required libraries

```bash
# conda
conda install anaconda::numpy
conda install anaconda::pandas
conda install anaconda::matplotlib
conda install anaconda::scikit-learn
conda install anaconda::jupyter
# pip
pip install numpy
pip install pandas
pip install matplotlib
pip install scikit-learn
```

### 4. Set the dataset path

recomended:

```bash
machine-learning-aplication/
```

## Functions

## 🐛 Troubleshooting

**Error: "download stopwords"**.

* **Email parsing - logistic_refression**

```python
# save under the user home directory
import nltk
nltk.download('stopwords')

# save to speific location
import nltk
import os

route_download = "/specific/location/nltk_data"
nltk.download('stopwords', download_dir=route_download)

if route_download not in nltk.data.path:
    nltk.data.path.append(route_download)
```

**Error: download arff**.

* **Import arff - data_splitting**

```bash
# pip
pip install arff

# conda
conda install auto::arff
```

## ❓ FAQ

* [How to activate conda environment](https://es.stackoverflow.com/questions/335525/como-activar-conda-environment/339487#339487)
* [Managing environments](https://www.anaconda.com/docs/tools/anaconda-navigator/tutorials/manage-environments)
* [What's Logistic Regression?](https://www.ibm.com/mx-es/think/topics/logistic-regression)

## Contact me & Social Media

![Email](https://img.shields.io/badge/Gmail-terrazasjosue0%40gmail.com-EA4335?style=for-the-badge&logo=Gmail&logoColor=white&labelColor=101010)
[![Facebook](https://img.shields.io/badge/Facebook-%40Josu%C3%A9_Terrazas-0866FF?style=for-the-badge&logo=Facebook&logoColor=withe&labelColor=101010)](https://facebook.com/josue.terrazasmendoza)
[![Instagram](https://img.shields.io/badge/Instagram-%40jos__mdz316-E4405F?style=for-the-badge&logo=Instagram&logoColor=white&labelColor=101010)](https://instagram.com/jos_mdz316/)
