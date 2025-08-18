### Creating Virtual Environments (3 Ways)

There are multiple ways to create a virtual environment. Below are three common approaches.

### 1. Using the Python `venv` module

- Execute the command:

```bash
python -m venv myenv
```

- Here, `myenv` is the folder that will be created and inside it the `venv` package will exist.

- To activate the environment, execute the `activate` script inside the `Scripts` folder:

```bash
myenv/Scripts/activate
```

- This will activate the virtual environment.

- Note: This will install the version of Python already installed on your system. To create a virtual environment of a different version, you need to upgrade your Python version in your system altogether.

- To deactivate the environment:

```bash
deactivate
```

### 2. Using the `virtualenv` package

- Install the package:

```bash
pip install virtualenv
```

- This installs the `virtualenv` package that will be responsible for creating the virtual environment. This package is mostly used for Linux-based systems.

- To create the environment:

```bash
virtualenv -p python3 virtual_env
```

- This will create a `virtual_env` folder which will have the `activate` script as well. To activate the environment:

```bash
virtual_env/Scripts/activate
```

- This will activate your `virtual_env` virtual environment.

- To deactivate the environment:

```bash
deactivate
```

### 3. Using `conda create`

This was already covered in Section 1 - Getting Started. For this you need to have Anaconda installed. 