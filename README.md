# eeg_MNE

### Step 1: Download Anaconda

Anaconda is a Python distribution that includes Python itself and many commonly used packages. Here's how to download and install Anaconda:

1. Go to the Anaconda download page: [Anaconda Download](https://www.anaconda.com/products/individual).

2. Choose the appropriate installer for your operating system (Windows, macOS, Linux). Make sure to download the Python 3.x version (e.g., Python 3.8 or later).

3. Follow the installation instructions for your operating system provided on the download page.

### Step 2: Download pip (if not included with Anaconda)

In most cases, Anaconda includes pip by default. You can check if it's installed by opening a terminal/command prompt and running:

```bash
conda list pip
```

If pip is not listed, you can install it using conda (the package manager that comes with Anaconda):

```bash
conda install pip
```

### Step 3: Download Jupyter Lab

Jupyter Lab is an interactive development environment for Python. You can install it using pip (make sure you have pip installed as mentioned in Step 2):

```bash
pip install jupyterlab
```

### Step 4: Create a Virtual Environment

A virtual environment allows you to isolate your Python environment for different projects. To create one, open a terminal/command prompt and follow these steps:

1. Create a new virtual environment (replace `<environment_name>` with your preferred name):

   ```bash
   conda create --name <environment_name> python=3.8
   ```

2. Activate the virtual environment:

   - On Windows:

     ```bash
     conda activate <environment_name>
     ```

   - On macOS and Linux:

     ```bash
     source activate <environment_name>
     ```

### Step 5: Download PyQt4

To install PyQt4 in your virtual environment, activate the environment (if not already activated) and then use pip to install PyQt4:

```bash
pip install PyQt4
```

### Step 6: Add the IPyP Script to Jupyter Lab

You can add an IPyP script (I assume you meant an IPython/Jupyter Notebook script) to Jupyter Lab by following these steps:

1. Activate your virtual environment (if not already activated).

2. Launch Jupyter Lab:

   ```bash
   jupyter lab
   ```

3. In the Jupyter Lab interface, navigate to the directory where your IPython/Jupyter Notebook script is located.

4. Create a new Python 3 notebook by clicking on the "+Python 3" button.

5. In the new notebook, you can paste and run your Python code.

Now, you should be all set to run your EEG analysis with my code within the Jupyter Lab environment, with PyQt4 installed in your virtual environment.

