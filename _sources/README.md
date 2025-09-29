# Equations of state (pyiron_workflow)
This repository demonstrates computing equations of state using the `pyiron_workflow` framework. The workflow is engine-agnostic and is demonstrated here with LAMMPS.

## Installation
Create and activate the conda environment from the provided `environment.yml`:

```bash
# Using mamba (recommended)
mamba env create -f environment.yml -n pyiron-workflow-equations-of-state
conda activate pyiron-workflow-equations-of-state

# Or using conda
conda env create -f environment.yml -n pyiron-workflow-equations-of-state
conda activate pyiron-workflow-equations-of-state

# To update an existing environment after changes to environment.yml
mamba env update -f environment.yml -n pyiron-workflow-equations-of-state
# or
conda env update -f environment.yml -n pyiron-workflow-equations-of-state
```

## Run the workflow
Open and execute the notebook `equations_of_state.ipynb` in this directory:

```bash
jupyter lab
# or
jupyter notebook
```

Then open `equations_of_state.ipynb` and run all cells.
