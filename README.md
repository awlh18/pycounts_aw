# pycounts

Calculate word counts in a text file!

[![codecov](https://codecov.io/github/awlh18/pycounts_aw/graph/badge.svg?token=9J2GCRHPJS)](https://codecov.io/github/awlh18/pycounts_aw)

## Installation

```bash
pip install pycounts_aw
```

## Usage

`pycounts_aw` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_aw.pycounts_aw import count_words
from pycount_aws.plotting_aw import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. 
Please note that this project is released with a Code of Conduct. 
By contributing to this project, you agree to abide by its terms.

## License

`pycounts_aw` was created by Alex Wong. It is licensed under the terms
of the MIT license.

## Credits

`pycounts_aw` was created with 
[`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and 
the `py-pkgs-cookiecutter` 
[template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
