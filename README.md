# ME276DS-SDSE-The-Happiness-Project

Project modeling and predicting a country's happiness score from a diverse set of features

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
  - [Packages](#packages)
  - [Environmental Variables](#environmental-variables)
- [Usage](#usage)
- [Conclusion](#conclusion)
- [Contributors](#contributors)

## Introduction

## Installation

To be able to run the project, you need to have Python installed on your machine.

The steps to install and run the project are as follows:

1. Clone the repository
2. Install the required packages
3. Setup environmental variables
4. Run the jupyter notebooks

### Packages

A python version compatible with tensorflow is required to run the project.

Packages needed for running project can be found in the `requirements.txt` file. To install all packages, create a virtual environment and run the following command:

**Creating virtual environment:**

```bash
python -m venv env #windows

python3 -m venv env #mac
```

**Activating virtual environment:**

```bash
env\Scripts\activate #windows

source env/bin/activate #mac
```

**Installing packages using pip:**

```bash
pip install -r requirements.txt #windows

pip3 install -r requirements.txt #mac
```

Select the virtual environment as the Python interpreter in the jupyter notebook.

### Environmental Variables

Create a `.env` file in the root directory of the project and add the following variables:

```bash
KAGGLE_USERNAME=your_kaggle_username
KAGGLE_KEY=your_kaggle_key
```

## Usage

The project is divided into two main parts:

- Data preprocessing
- Data analysis

1. To run the project first activate the virtual environment and then run the jupyter notebook.
2. Then run through data_preprocessing.ipynb notebook in order to generate the needed data (if not already present) and then run the data_analysis.ipynb notebook to analyze the data and train the model.
3. Read the detailed report for interpretation of the results and metholody.

## Conclusion

The conclusion of the project can be read in the report.

## Contributors

- [Trygve Nummedal Os](https://github.com/Zafewood)
- [Christian Veiby](https://github.com/christianveiby)
- Ebba Maja Olsson
- Annette Gjersøyen
- Emma Benum
