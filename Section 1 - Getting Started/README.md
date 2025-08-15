# Getting Started with Data Science

## What is Anaconda?

Anaconda is a powerful distribution that simplifies installing, managing, and working with Python (and R) for data analysis, machine learning, and scientific computing.

## Key Benefits of Anaconda

### 1. Package Management
- **Conda Package Manager**: A powerful package manager that handles installing and updating libraries (like NumPy, pandas, scikit-learn) without dependency headaches
- **Better Binary Support**: Works better than pip for some scientific packages that require compiled binaries (like NumPy with optimized BLAS)

### 2. Environment Management
- **Isolated Environments**: Create isolated environments with specific versions of Python and libraries, avoiding conflicts between projects
- **Example Use Case**: You can have one project on Python 3.8 with TensorFlow 2.4 and another on Python 3.11 with PyTorch without breaking either

### 3. Preinstalled Data Science Stack
- **Comprehensive Library Collection**: Ships with 1,500+ popular data science and machine learning libraries already included
- **Key Libraries**: pandas, NumPy, Matplotlib, SciPy, Jupyter Notebook, etc.
- **Time Saving**: Saves time compared to installing everything manually

### 4. Jupyter & Development Tools
- **Integrated Tools**: Integrates with Jupyter Notebook/Lab, Spyder, and VS Code
- **Interactive Analysis**: Makes interactive data analysis easy with built-in visualization and exploration tools

## Summary
Anaconda is like a Swiss Army knife for data scientists — it packages Python, R, and all the tools you need in a way that's easy to install, manage, and replicate.

## Best Practices for Project Setup

### Creating Virtual Environments
For any projects you work on, it's always a best practice to launch a separate environment for it.

**To create a virtual environment, execute this command at the root level:**
```bash
conda create -p venv python==3.10
```

This will create a `venv` folder at the root level and we'll be executing our projects inside this virtual environment itself.

### Activating the Virtual Environment
**To switch to venv, execute the command:**
```bash
conda activate venv
```

Now whatever commands we run on the terminal, those will be executed inside this environment.

### Installing Required Libraries
We'll be making extensive use of the scikit-learn library throughout this course. 

1. **Create a requirements.txt** at the root directory
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

This will install the scikit-learn library inside the virtual environment.

### Running Jupyter Notebooks
**To run Jupyter Notebooks in .ipynb format, first install this package:**
```bash
pip install ipykernel
```

## Next Steps
- Set up your virtual environment
- Install required dependencies
- Start exploring with Jupyter Notebooks 