# A forcefield parametrization of NaSCN and KSCN 

Ionic parameters appearing in the Lennard-Jones potential are optimized to reproduce thermodynamic properties obtained from experiments.

## Running the Jupyter notebook

You can run it in the web browser on mybinder (without installing anything) by clicking the link [here](https://mybinder.org/v2/gh/vaspelin/thiocyanate/master?filepath=project_updated.ipynb) (ignore the following in that case).


1. Install miniconda3 or anaconda3 on your computer.
2. Download the repository by downloading it directly, or by typing the following in a terminal:
```bash 
git clone https://github.com/teokem/project-work-vaspelin/
```
3. When you are in the folder that you just downloaded, activate the environment contained in the file [`environment.yml`](/environment.yml) by typing the following in a terminal:
```bash 
conda env create -f environment.yml
source activate analysis
```
4. Open the Jupyter notebook `project_updated.ipynb` by typing the following in a terminal:
```bash
jupyter notebook project_updated.ipynb 
```
5. Reproduce the study by running the cells in the notebook.

