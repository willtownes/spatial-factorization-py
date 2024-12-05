# spatial-factorization-py
Probabilistic factor models for spatially correlated data. Includes nonnegative and real-valued versions.

## Installation
Many people find it convenient to install everything in a conda environment. We recommend installing the [miniforge](https://conda-forge.org/miniforge/#latest-release) version of conda. You can then create an environment and activate it with the following commands:
```sh
conda create -n nsf python=3.11
conda activate nsf
```
The package can then be installed into the environment from github: 
```sh
pip install git+https://github.com/willtownes/spatial-factorization-py.git#egg=spatial-factorization
```

## Usage
```python
import spatial_factorization
help(spatial_factorization.ModelTrainer)
help(spatial_factorization.SpatialFactorization)
```

## Development
### Building locally with hatch
First make sure that the right tools are installed:
```bash
pip install hatch
pip install keyrings.alt
```
Then build with hatch:
```
hatch build
```
