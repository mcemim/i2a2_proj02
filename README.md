# template_ds_project

<p align="center">
  <a href="" rel="noopener">
 <img width=300px height=95px src="https://raw.githubusercontent.com/dududzainer/termicalogos/main/TERMICA.png" alt="Project logo"></a>
</p>

<h3 align="center">TERMICA - Projeto 02</h3>
<h3 align="center">Projeto 02 I2A2 - Pump sensor data for predictive maintenance</h3>

<div align="center">

  [![code coverage](coverage.svg "Code coverage")]()
</div>

---


## 🧐 About <a name = "about"></a>

Projeto 02 I2A2 - Pump sensor data for predictive maintenance

## 🔖 Project structure

```
i2a2_proj02/
|- bin/          # contains scripts and main files that should be run
|- config/       # config files
|- data/         # local data files needed for the project
|- notebooks/    # notebooks for EDA and exploration
|- secrets       # contains api keys and secret parameters. It should be ignored from git
|- src/          # source code - contains functions
|- tests/        # Test files should mirror the src folder
|- Makefile      # automatize taks through make utility
```
Structure based on https://github.com/kaislar/ds_template


## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Clone the project 
```
git clone git@github.com:mcemim/i2a2_proj02.git
```

## Setup your environement and install project dependencies
```
conda create -n Projeto 02 I2A2 - Pump sensor data for predictive maintenance python=3.11
source activate Projeto 02 I2A2 - Pump sensor data for predictive maintenance


python -m pip install pip-tools
pip-compile --output-file requirements.txt requirements.in requirements_dev.in
python -m pip install -r requirements.txt
```

### Installing

## 🔧 Running the tests
Tests are implemented in ./tests, you need to run the following command to run them.
```
make tests
```

## 🚀 Deployment
Add additional notes about how to deploy this on a live system.

## 🎈 Contributions
To contribute in this project, please setup locally the project following the steps  in Getting started section.
We use few packages to guarantee high quality code. Before commiting you can run:
To format you code using black
```
make black
```
To get warning message on non respect of pep8 code guidance:
(the command runs on all .py files in the project)
```
make lint
```
You can also run automatically, black, lint and few other packages to analyze and check your code base before commiting
```
make precommit
```

##  ✍️ Authors
Marcos Cemim - mcemim@gmail.com
