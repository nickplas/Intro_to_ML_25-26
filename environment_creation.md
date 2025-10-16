# This file shows how to create a virtual environment for your local project

> python3 -m venv ./virtual_environment_name           # Here you create a venv with your predefined python 3 version,    
                                                       # you can change it by using, for example, python3.10 ...

> source ./virtual_environment_name/bin/activate       # Activate your venv

> pip list                                             # Check the installed python packages

> pip install python_package_name                      # Install a py package

> pip uninstall python_package_name                    # Uninstall py package

> deactivate                                           # Turn off venv


### Attention

Do not push your virtual environment in your github repo!
Instead upload the requirements (aka the python packages
that are installed)

To do so (inside your environment):

> pip freeze > requirements.txt                        # Creates a txt with all your dependencies

> pip install -r requirements.txt                      # Install all the requirements in your txt

And then push your requirements.txt file to git

> git add requirements.txt

> git commit -m 'adding requirements'

> git push



For othet tips and tricks: https://realpython.com/what-is-pip/
