# wikidata
CMPT 353 D1 Project - On Wikidata, Movies, and Success
by Jason Wang, Matthew Chan

<b>Required libraries</b>
import numpy as np
import pandas as pd
import sys
import matplotlib
import matplotlib.pyplot as plt
from skimage.color import lab2rgb
from sklearn.model_selection import train_test_split
from sklearn.naive_bayes import GaussianNB
import skimage
from sklearn.pipeline import make_pipeline
from sklearn.preprocessing import FunctionTransformer
from sklearn.neighbors import KNeighborsClassifier
from sklearn.svm import SVC
from functools import reduce
import statsmodels.api as sm
lowess = sm.nonparametric.lowess
from scipy import stats

<b>Commands</b>
You can open the ipnyb file using Jupyter or run the python file:
$ python <file_name>

<b>Files produced/expected</b>
Results should be printed as usual or as separate diagram windows

