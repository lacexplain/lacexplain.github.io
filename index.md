# LACE project page  
----

LACE is a model-agnostic explanation method that explains the individual predictions of any classifier. The influence of both single attributes, and attribute subsets on the prediction for specific instances is quantified by omitting attribute sets and measuring the prediction change. We overcome the exponential time complexity that derives from the computation of the power set of the feature values by learning a local model. The local model is an associative classifier that is learned in the locality of the instance whose prediction is to be explained. It returns the subsets of feature values that are relevant for that particular prediction. Only these subsets are omitted. Experiments performed both on synthetic and real-world data sets highlighted the ability of the LACE explanation method to capture all relevant attribute subsets that jointly contribute to a single instance prediction


Usage - Notebooks
-----
At the following notebook [**running example - zoo dataset**](https://github.com/elianap/LACE/blob/main/00_LACE_Running_Example_ZOO_X-PLAIN.ipynb) you can find a running example of the usage of LACE

Source code
-----
The source code is available at the following [link](https://github.com/elianap/LACE)
