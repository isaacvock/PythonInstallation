# PythonInstallation
Step-by-step instructions to install Python and Jupyter notebooks.

## Quickstart

1. Install Miniforge 3
      - For the Mac (or Linux??) users, open a terminal and run these two lines of code (one line at a time!):

    ```
    curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"
    bash Miniforge3-$(uname)-$(uname -m).sh
    ```

    or if that doesn't work for you:

    ```
    wget "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"
    bash Miniforge3-$(uname)-$(uname -m).sh
    ```
     - For Windows users, download the installer by clicking [this link](https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge-pypy3-Windows-x86_64.exe). Then follow the prompts keeping all o the default settings.

1. Download the environment file from this repository (click on file, then click on download button at top right of file display).

2. Create the conda environment

   - Go to where the environment.yaml file is on your file system and run:
  
     ```
     mamba env create -f environment.yaml
     ```

    - If you are a Windows user, you will have to do this in the Miniforge Prompt. Find this by searching for it in your Start menu

3. Test it out by opening a Jupyter notebook

   - Activate the environment: `conda activate mbb121L`
   - Start a Jupyter notebook by running: `jupyter notebook`
