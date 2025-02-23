# Libraries, Packages, and modules

- A **library** is a collection of reusable code modules. These are bundled into **packages**, which can then be imported into the coding environment as required.
- **Modules** are similar to libraries, in that they are groups of related classes and functions, but they are generally subcomponents of libraries.

## import statements

  - Libraries and packages can be used interchangeably. It typically must be imported into the working environment as per required.
  - To import a library or module, use an import statement where **import** is the keyword.
```
    import numpy
    import pandas
    import matplotlib.plyplot
```
## Aliasing

Aliasing helps to avoid typing a library's full name everytime you want to access. It is an abbreviated name, designed using the **as** keyword.
```
import numpy as np
import pandas as pd
```
NumPy is used for high performance vector and matrix computations. Pandas is a library for manipulating and analyzing tabular data. Seaborn and matplotlib are both libraries used to create graphs, charts, and other data visualizations.

## Commonly used built-in modules

The python standard library comes with a number of built-in modules relevant to data professional work such as **math**, **datetime**, **random**.

**datetime** : provides many helpful date and time conversions and calculations
``` import datetime
    date = datetime.date(1979, 4, 6)
    print(date)
    print(date.year)
```

**math**: provides access to mathematical functions.
``` import math
    print(math.exp(0))
    print(math.log())
```

**random**: useful for generating pseudo-random numbers.
