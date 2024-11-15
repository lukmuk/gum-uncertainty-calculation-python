# GUM Uncertainty Calculation with Python

Exploring uncertainty calculation and testing examples in the official GUM (**G**uide to the expression of **u**ncertainty in **m**easurement) document ([https://doi.org/10.59161/JCGM100-2008E](https://doi.org/10.59161/JCGM100-2008E)) using Python, particularly the [uncertainties](https://pythonhosted.org/uncertainties/index.html) package.

Packages installed (you may change `mamba` to `conda`):  
```
mamba install -c conda-forge jupyterlab numpy matplotlib scienceplots watermark ipympl uncertainties scipy
```
Alternatively, use the provided `yml` file and change the `ENV_NAME` to your desire, e.g. `gum`:

```
mamba env create -n ENV_NAME -f environment.yml
````

An `html` export of the notebook is provdided for quick inspection in a browser/mobile.