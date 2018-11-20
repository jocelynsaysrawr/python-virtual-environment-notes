# Python Virtual Environments - Setup/Notes

[Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/)

#### What is a Python Virtual Environment?

* An isolated environment for each project.
* Virtual environments are used to keep dependencies for different projects seperate. This is to ensure that projects using different versions of the same site packages (third-party libraries) don't interfere with each other.

#### Using Virtual Environments

* `mkdir <project name> && cd <project name>`
    * create a new project directory and cd into it
* `python3 -m venv env`
    * create a new virtual environment inside of the project directory

![create-python-virtual-environment](img/py-venv-demo.png)
