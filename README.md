# wikidata
CMPT 353 D1 Project - On Wikidata, Movies, and Success
by Jason Wang, Matthew Chan

<b>Required libraries</b>
<l>import numpy as np</l>
<l>import pandas as pd</l>
<l>import sys</l>
<l>import matplotlib</l>
<l>import matplotlib.pyplot as plt</l>
<l>from skimage.color import lab2rgb</l>
<l>from sklearn.model_selection import train_test_split</l>
<l>from sklearn.naive_bayes import GaussianNB</l>
<l>import skimage</l>
<l>from sklearn.pipeline import make_pipeline</l>
<l>from sklearn.preprocessing import FunctionTransformer</l>
<l>from sklearn.neighbors import KNeighborsClassifier</l>
<l>from sklearn.svm import SVC</l>
<l>from functools import reduce</l>
<l>import statsmodels.api as sm</l>
<l>lowess = sm.nonparametric.lowess</l>
<l>from scipy import stats</l>

<b>Commands</b>
You can open the ipnyb file using Jupyter or run the python file:
$ python <file_name>

<b>Files produced/expected</b>
Results should be printed as usual or as separate diagram windows

