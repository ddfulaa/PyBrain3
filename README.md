# PyBrain3
Just a modification of the PyBrain3 version installed using pip install pybrain3. That library has wrong some headers, and try import Random from Scipy. I've just changed Scipy by Numpy.


# How to use it in Google Colab

```
import sys
sys.path.insert(0, 'local_pybrain path')
import pybrain3
```
