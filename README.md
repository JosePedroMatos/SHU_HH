# SHU
 Support elements for teaching hydrology and hydrogeology using Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JosePedroMatos/SHU_HH.git/HEAD)


To install this locally, the following is recommended:
- Download Anaconda (or Miniconda, which saves space) from https://www.anaconda.com/download/success?reg=skipped
- Install it.
- Download environment.yml from this project (this is the blueprint of the Python environment you will need).
- Open anaconda prompt and navigate to the folder where environment.yml was saved.
- Still in anaconda prompt, install the "shu_hh" environemnt. To do so, type the following:
    - conda install -n base conda-libmamba-solver #This installs a solver for compatibility that is preferred.
    - conda config --set solver libmamba #This applies it.
    - conda env create -f environment.yml #This line actually installs the environment. May require confirmation. Will take a long time.
    - conda activate shu_hh # This activates the environment.
    - python -m ipykernel install --user --name=shu_hh # this registers the jupyter kernel.
- The environment call be activated by typing 'conda activate shu_hh' in anaconda prompt.
- Install VSCode from https://code.visualstudio.com/.
- In VSCode, install at least the following extensions:
    - Python.
    - Jupyter.
- Download the contents of the project and open the folder in VSCode.
- You should then be able to run the .ipynb files.