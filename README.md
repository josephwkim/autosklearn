# **autosklearn**
#### Automated selection of the best scikit-learn model for your data.

To install, download this repo and move it to `site-packages` folder within your python 3 distribution.  (Anaconda3 etc.)

This library only has support for supervised learning (regression, classification) at the moment. To run regression models, use the following commands:
```
from autosklearn.supervised import regressor
# your code here
results = regressor(x_train, x_test, y_train, y_test)
# results will be initialized as pandas Series object.
```
For classification:
```
from autosklearn.supervised import classifier
# your code here
results = classifier(x_train, x_test, y_train, y_test)
# results will be initialized as a pandas Series object.
```

Dependencies:
- scikit-learn
- numpy
- pandas

This should be compatable for mac, windows, and unix but has only been tested on windows.


*Disclaimer:*
*This code is trash and was a proof of concept.  A productionalized version is in development and will be published to PyPi at my earliest convenience*
