# spatial-factorization-py
Probabilistic factor models for spatially correlated data. Includes nonnegative and real-valued versions.

## Installation
From github: 
```sh
pip install git+https://github.com/willtownes/spatial-factorization-py.git#egg=spatial-factorization
```
Pypi coming soon.

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
