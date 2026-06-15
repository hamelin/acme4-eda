# Exploratory analysis on ACME4

Get the dataset [here](https://gdo168.llnl.gov/data/ACME4/stdview-20240819-20240923/).

This repository presumes you will use [uvk](https://github.com/hamelin/uvk) to put together kernels with the proper dependencies.
This table shows you how to set up.

|  | Using **uv**   | Using an ad hoc virtualenv$^1$ |
|-:|:--------------:|:--------------------------:|
| Running my own Jupyter Lab | `uv run jupyter lab` | `pip install -e .`<br>`jupyter lab` |
| Through JupyterHub         | `uvx uvk install --user` | `pip install -e .`<br>`uvk install --user` |

$^1$ This assumes one has created and activated this ad hoc virtualenv:
   ```sh
   python -m venv .venv
   . .venv/bin/activate
   ```
