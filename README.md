Note that this is a fork from the repository: https://github.com/jotaraul/uma_robotics_2023

The intention is that us, the students, complete some parts of the given code. 

![UMA ROBOTICS 2023](https://github.com/jotaraul/uma_robotics_2023/blob/main/utils/logo_uma_robotics_2023.png "UMA ROBOTICS 2023 logo")

Working repository for the Robotics subject at the University of Málaga (2022-2023 edition). Powered by the [Machine Perception and Intelligent Robotics Group (MAPIR)](http:mapir.isa.uma.es).

You can create a docker with an image of this repo here: &nbsp; [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Javi-M/uma_robotics_2023/HEAD)

---

# Summary _(kind of table of content & cheat sheet)_
## Chapter 1. Welcome

:books: **Libraries** and **modules**:
* NumPy [(docs)](https://numpy.org/doc/stable/reference/)
* SciPy [(docs)](https://docs.scipy.org/doc/scipy/reference/)
* matplotlib [(docs)](https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html)
    * matplotlib.pyplot
     

```python
import numpy as np
from numpy import random
from scipy.special import perm

import matplotlib.pyplot as plt

import ipywidgets as widgets
from ipywidgets import interact, interactive, fixed, interact_manual
```

**Functions and methods in this section**:
`np.array([...])`, `np.vstack([...])`, `np.hstack([...])`,
`np.diag([...])`, `scipy.linalg.inv()`, `A@B`, `plt.plot()`,
`plt.figure()`, `plt.subplots()`, `h.pop(0).remove()`

## Chapter 2. Probability and Satatistics Bases for Robotics
### 2.1 Probability and Statistics Bases for Robotics
#### 2.1.1 The gaussian distribution

**Functions and methods in this section**:
`np.linspace()`, np.pi

# Glossary
| Function/method | From library/module | In chapter/s... | What does it do? |
|-----------------|---------------------|-----------------|------------------|
| `array`         | `numpy`             | 1.2
| `diag`          | `numpy`             | 1.2
| `figure`        | `matplotlib.pyplot` | 1.2
| `hist`          | `matplotlib.pyplot` | 1.2             
| `hstack`        | `numpy`             | 1.2
| `inv`           | `scipy.linalg`      | 1.2             | Compute the inverse of a matrix |
| `perm`          | `scipy.special`     | 1.2
| `plot`          | `matplotlib.pyplot` | 1.2
| `vstack`        | `numpy`             | 1.2

| Others          | From library/module | In chapter/s... | What does it do? |
|-----------------|---------------------|-----------------|------------------|
| `A@B`           | `numpy.ndarray`     | 1.2             | Matrix multiplication |      