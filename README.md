create env
'''bash 
conda create -n wineq python=3.7 -y
'''

activate env 
'''bash
conda activate wineq
'''


created a requirements file 

install the requirements
'''bash
pip install -r requirements.txt
'''

git init

dvc init


dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

oneliner update for readme
git add . && git commit -m "update Readme.md"

git remote add origin https://github.com/MKchethan/simple-dvc-demo.git

git branch -M main

git push origin main