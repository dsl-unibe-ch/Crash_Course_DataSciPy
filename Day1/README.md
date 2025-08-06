# Introduction

## Get the material

If you have not done so already, you can obtain the course material by clicking on the green "Code" button at the top of this page and then selecting "Download ZIP". Alternatively, you can clone the repository using Git.

## Environment setup: conda

To be able to run the notebooks and exercises for the course, you will need to setup a Python environment. There are multiple solutions to do this, but we recommend using conda, a package manager that simplifies the installation of Python and its libraries. Conda comes in multiple flavors but we recommend using [Miniforge](https://github.com/conda-forge/miniforge?tab=readme-ov-file#download) which is a minimal installer for conda that includes only the packages from the conda-forge channel. Follow the [installation instructions](https://github.com/conda-forge/miniforge?tab=readme-ov-file#install) to install Miniforge on your system.

On Windows, you can download the installer and run it. After the installation you can get access to conda via a terminal, the Miniforge Prompt.

On macOS and Linux, installation happens via the terminal. Follow the instructions you see on the screen. Towards the end of the installation you will be asked whether you want to initialize conda. The default answer is no **but you should answer yes**. This will make sure that upon closing and reopening the terminal, conda will be available. If you accidentally answered no, you can run the following command to initialize conda:

```bash
~/miniforge3/bin/conda init
```

## Create a conda environment

Now that you have conda installed you can create a conda environment. For this you can use the `environment.yml` file that is provided in this folder. Open a terminal (or the Miniforge Prompt on Windows) and navigate to the Day1 folder. If you don't know the path, you can drag and drop the folder into the terminal which will give you the path. Once you are in the Day1 folder, run the following command:

```bash
conda env create -f environment.yml
```
This will create a conda environment called `DSPy2025` with all the necessary packages installed. You can use the environment by running:

```bash
conda activate DSPy2025
```

In VSCode, you can also select the conda environment as the interpreter for your notebooks. Open the Command Palette (Cmd+Shift+P on macOS or Ctrl+Shift+P on Windows/Linux) and type "Python: Select Interpreter". Then select the `DSPy2025` environment from the list.