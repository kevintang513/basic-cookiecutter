# Basic Data Science Cookiecutter

Basic cookiecutter setup to create new data science project directories consistently and with a focus on keeping the project clean and to maintain up to date notes about the state of the project. This was designed to include everything that is needed to quickly set up a new project for a specific workflow so feel free to delete or change the project files or directories once it's created. If you have anything you would like to add or change feel free to create a branch with ideas or changes.


### Requirements to use this cookiecutter template:
-----------
 - Python 3.5+
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This along with it's dependencies can be installed using the following commands:

``` bash
pip install jinja2-ospath
pip install cookiecutter
```


### To start a new project:
------------

Either run the command using the link to the gitlab repository:

    cookiecutter https://github.com/kevintang513/basic-cookiecutter

Or you can clone the repository locally and run the following command:

    cookiecutter path/to/template/

You will then be asked for the details of the project. Once the details have been provided, a new directory will be created for the project within the directory you are in. From there, setup your virtual environment and install the dependencies the Pipfile and you are good to go. The new project directory is not itself a git repository yet so initialize git and a .gitignore should be there to prevent some of the directories from being included in the repository. 

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
default_project/
├── data                                <- Where data should be located
├── default_project.py                  <- A simple hello world to test the environment
├── notebooks                           <- Where Jupyter notebook should be located
├── Pipfile                             <- pipenv package list
├── plots                               <- Where plots should be saved
├── README.md                           <- A description of the project
└── results                             <- Where computed results should be saved
```
