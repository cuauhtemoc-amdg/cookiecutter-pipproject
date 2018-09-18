# cookiecutter-pipproject
Pip-installable cookiecutter template for python projects intended to be pip-installed:

[cookiecutter](https://github.com/audreyr/cookiecutter)

Inspired by: [wdm0006](https://github.com/wdm0006/cookiecutter-pipproject.git)


Using CookieCutter for your project
-----------------------------------

    $ pip install cookiecutter
    $ cookiecutter https://github.com/cuauhtemoc-amdg/cookiecutter-pipproject.git

You will be asked about your basic info (name, project name, app name, etc.). This info will be used in your new project.


Publishing your project to pypi
-------------------------------

There are two ways to publish your project:

 * the manual way, outlined [here](http://www.willmcginnis.com/2015/11/12/create-a-pip-installable-python-package-in-2-minutes/)
 * and with pypi-publisher [ppp](https://github.com/wdm0006/pypi-publisher)
 
Goals
-----

The goal of this project is to create a python project template that includes these features:

 * Sphinx documentation
 * Installable via pip in pypi
 * Testing via Nose and Coverage
 
License
-------

MIT licensed.
