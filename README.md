# wikidata
CMPT 353 D1 Project - On Wikidata, Movies, and Success
by Jason Wang, Matthew Chan

<b>Required libraries</b>
<br>import numpy as np<br>
import pandas as pd<br>
import sys<br>
import matplotlib<br>
import matplotlib.pyplot as plt<br>
from skimage.color import lab2rgb<br>
from sklearn.model_selection import train_test_split<br>
from sklearn.naive_bayes import GaussianNB<br>
import skimage<br>
from sklearn.pipeline import make_pipeline<br>
from sklearn.preprocessing import FunctionTransformer<br>
from sklearn.neighbors import KNeighborsClassifier<br>
from sklearn.svm import SVC<br>
from functools import reduce<br>
import statsmodels.api as sm<br>
lowess = sm.nonparametric.lowess<br>
from scipy import stats<br>

<b>Commands</b>
You can open the ipnyb file using Jupyter or run the python file:
$ python <file_name>

<b>Files produced/expected</b>
Results should be printed as usual or as separate diagram windows

