[![CI](https://github.com/jkaur2026/ids568-milestones/actions/workflows/ci.yml/badge.svg)](https://github.com/jkaur2026/ids568-milestones/actions/workflows/ci.yml)
# ids568-milestones

Setting up from scratch

You are going to clone the repo by:
1) git clone https://github.com/jkaur2026/ids568-milestones.git
cd ids568-milestones

You are going to initialize the virtual environment by:
2) -m venv venv 
source venv/bin/activate

You are going to install the dependencies by:
3) pip install --upgrade pip then you are going to do pip install numpy pandas scikit-learn pytest and then you are going to do pip freeze > requirements.txt. 

You are going to make the test and then you are going to run the smoke test by:
mkdir tests nano tests/test_imports.py
def test_imports():
import numpy
import pandas
import sklearn


