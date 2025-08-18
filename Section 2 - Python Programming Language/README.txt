1. There are multiple ways to create a virtual environment, I will be showing you 3 ways to do it.

a. Using Python Command

Execute the command: python -m venv myenv

Here, myenv is the folder that will be created and inside that venv package will exist.

Now, to activate the environment, there is an activate script inside the Scripts folder inside myenv, we just need to execute that script by specifying the path of the script: myenv/Scripts/activate

This will activate the virtual environment

Note: This will install the version of Python which you have already installed in your system. To create virtual environment of a different version, you need to upgrade your python version in your system altogether.

To deactivate the environment, just execute the command 'deactivate'

b. Using virtualenv package

Execute the command: pip install virtualenv

This will install a virtualenv package that will be responsible for creating the virtual environment. This package is mostly used for Linux based systems.

To create the environment, execute the command: virtualenv -p python3 virtual_env

This will create a virtual_env folder which will have the activate script as well. To activate the environment: virtual_env/Scripts/activate

This will activate your virtual_env virtual environment.

To deactivate the environment, just execute the command 'deactivate'

c. Using conda create command

This we have already covered in Section 1 - Getting Started. For this you need to have Anaconda installed.


2.