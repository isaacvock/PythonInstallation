# PythonInstallation
Step-by-step instructions to install Python and Jupyter notebooks.

## Quickstart

1. Install Miniforge 3

    - For the Mac (or Linux??) users, open a terminal and run:

```
curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"
bash Miniforge3-$(uname)-$(uname -m).sh
```

or if that doesn't work for you:

```
wget "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"
bash Miniforge3-$(uname)-$(uname -m).sh
```

    - For Windows users, download the installer by clicking [this link](https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge-pypy3-Windows-x86_64.exe). Then follow the prompts keeping all of the default settings.

1. Create the conda environment that will house all of the tools used in this class:

    - For Mac/Linux users, that means
