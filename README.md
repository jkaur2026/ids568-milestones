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

8) Next you are going to GitHub and go to the repo, actions tab and it should a green mark that means it is good and working. You can add the CI badge by going to the actions tab then it should show workflow, click "create status badge" which then you can copy that and then paste it in to your README.md (then go back to the main page and it should show a green mark which is the badge and you are good to go. 

Written Document Portion
1) Environment reproducibility is something that is very importantfor the ML lifecycle reliability. That is because of the reason that its important that there is the the same results across everything otherwise it can cause problems in the code and the modesl so to stop this from happening it would be done by making a virtual environemnt and pinning dependencies as shown in the instructions on the requirements.txt.
2) The key reproducibility principles that were applied in my setup were making sure there is virtual environment and making there was a smoketest that was done to make sure it working well and I had used pytest for that. I also had pinned dependencies with the exact versions. I also then did GitHub actions to run everything and validating with the badge and making sure its green.
3) Strong environment helps make sure there is good deployment success because it needs to make everything is going smooth and such 

