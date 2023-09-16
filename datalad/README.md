# The DataLad part

This folder contains a Jupyter notebook with the DataLad walkthrough.
The notebook uses [Bash kernel](https://github.com/takluyver/bash_kernel).

To run the notebook, you need to have **DataLad** and its external dependencies, **Git** and **git-annex** installed.
Several installation methods are available, and are covered in [DataLad handbook](https://handbook.datalad.org/en/latest/intro/installation.html#install) or on [DataLad's website](https://www.datalad.org/#install).
Additionally, you need two DataLad extensions: **datalad-next** and (optionally) **datalad-containers** (both available as Python packages, through pip).
For our examples, we will also need the following Python packages: **black**, **nilearn** and **matplotlib**.

## Example installation

This is an example setup with virtualenvwrapper.
It relies on system-wide Git and git-annex installation, but installs all Python dependencies (including Jupyter) in the virtual environment.

```
# create virtual environment
mkvirtualenv incf2023

# install Jupyter and bash kernel
pip install jupyterlab bash_kernel
python -m bash_kernel.install --sys-prefix

# developer only: install nbstripout for nicer diffs
pip install nbstripout
nbstripout --install

# install datalad and its extensions
pip install datalad datalad-next==1.0.0b3 datalad-container

# install packages needed for examples
pip install black nilearn matplotlib
```

Many users prefer using conda to install DataLad, Git, and Git-annex (which does not preclude using pip for other dependencies).
Feel free to adjust accordingly.

## Slides

Accompanying slides can be found at https://mslw.github.io/Neuroinformatics2023-slides/workshop.html
