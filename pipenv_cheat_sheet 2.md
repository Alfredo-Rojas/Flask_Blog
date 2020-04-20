# Pipenv Cheat Sheet

## Install pipenv
```
pip3 install pipenv
```
## Activate
```
pipenv shell
```
## Check version of Python
```
python --version
```
## Check path
```
python
>>> import sys
>>> sys.executable
quit()
```
## Install a package
## Here camelcase is the name of the package to be installed
```
pipenv install camelcase  
```
## Check local packages
```
pipenv lock -r
```
## Uninstall a package
```
pipenv uninstall camelcase  
```
## Install a dev package
## Here 'nose' is the package to e installed as a dev dependency
```
pipenv install nose --dev
```
## Install from requirements.txt
```
pipenv install -r ./requirements.txt
```
## Check security vulnerabilities
```
pipenv check
```
## Check dependency graph
```
pipenv graph
```
## Set lockfile - before deployment
```
pipenv lock
```
## Ignore pipfile
```
pipenv install --ignore-pipfile
```
## Exiting the virtualenv
```
exit
```
## Run with pipenv
```
pipenv run *
```

############
## Initiate your project
```
cd desktop
mkdir <project_name>
```
## Creating the venv(the second venv is the name of the venv folder)
python3 -m venv venv
## Activating
```
source venv/bin/activate
```
## Check the version of python
```
which python
```
## To export the same requirement of your packages to a txt file for use the exactly packeges
```
pip freeze > requirements.txt
```
## To check the txt file created
cat requirements.txt
## How to see the package installed
```
pip list or pip freeze
```
## Delete the virtual enviroment
```
rm -rf venv/
```
## To deactivate the venv in terminal
```
deactivate
```
## Install from requirements.txt
```
pip install -r ./requirements.txt
```
## Creating a venv with access to the global enviroment
```
python3 -m venv venv --system-site-packages
```
# Activating
```
source venv/bin/activate
```
