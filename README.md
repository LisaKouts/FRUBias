# Using fuzzy-rough sets to measure bias in pattern classification problems

This python package contains a bias metric based on the paper *"A fuzzy-rough uncertainty measure to discover bias encoded explicitly or implicitly in features of structured pattern classification datasets"* ([Link to publication](https://doi.org/10.1016/j.patrec.2022.01.005)). 

This bias metric measures the extent to which a feature in a dataset influences the outcome variable.  

fairfru ([see here](https://pypi.org/project/FairFRU/)) is a Python package providing algorithms able to quantify fairness in automated decision making using the fuzzy-rough set theory. 

## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install FairFRU.

```bash
pip install fairfru
```
## Usage
```python
import fairfru
```

See the `Measuring_bias.ipynb` notebook in the `src/fairfu` folder for an example.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
