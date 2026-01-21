[![CI](https://github.com/jkaur2026/ids568-milestones/actions/workflows/ci.yml/badge.svg)](https://github.com/jkaur2026/ids568-milestones/actions/workflows/ci.yml)
# ids568-milestones

Setting up from scratch

1) You are going to clone the repo by:
git clone https://github.com/jkaur2026/ids568-milestones.git
cd ids568-milestones

2) You are going to initialize the virtual environment by:
-m venv venv 
source venv/bin/activate

3) You are going to install the dependencies by:
pip install --upgrade pip then you are going to do pip install numpy pandas scikit-learn pytest and then you are going to do pip freeze > requirements.txt. 

4) You are going to make the test and then you are going to run the smoke test by:
mkdir tests nano tests/test_imports.py
def test_imports():
import numpy
import pandas
import sklearn

5) In order to run the test you are going to then do (it should show pass):
pytest -q

6) Next you are going to set up the GitHub Actions by:
mkdir -p .github/workflows
nano .github/workflows/ci.yml


