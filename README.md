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
(then you are going to write out your workflow code into that and save it)

7) You are going to do the push the GitHub by:
git add .github/workflows/ci.yml requirements.txt tests/test_imports.py 
git
git commit -m "Milestone 0"
git push origin main

8) Next you are going to GitHub and go to the repo, actions tab and it should a green mark that means it is good and working. You can add the CI badge by going to the actions tab, workflow, click "create status badge"


