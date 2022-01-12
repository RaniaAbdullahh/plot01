### Install jupyterlab and ipympl.

For pip users:

pip install --upgrade jupyterlab ipympl
For conda users:

conda update -c conda-forge jupyterlab ipympl
Restart JupyterLab.

Decorate the cell containing plotting code with the header:

```%matplotlib widget```