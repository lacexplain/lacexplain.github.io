# LACE project page  
----

LACE is a model-agnostic explanation method that explains the individual predictions of any classifier. The influence of both single attributes, and attribute subsets on the prediction for specific instances is quantified by omitting attribute sets and measuring the prediction change. We overcome the exponential time complexity that derives from the computation of the power set of the feature values by learning a local model. The local model is an associative classifier that is learned in the locality of the instance whose prediction is to be explained. It returns the subsets of feature values that are relevant for that particular prediction. Only these subsets are omitted. Experiments performed both on synthetic and real-world data sets highlighted the ability of the LACE explanation method to capture all relevant attribute subsets that jointly contribute to a single instance prediction.




## Usage - Notebooks

At the following notebook [**running example - zoo dataset**](https://github.com/elianap/LACE/blob/main/00_LACE_Running_Example_ZOO_X-PLAIN.ipynb) you can find a running example of the usage of LACE

## Source code

The source code is available at the following [link](https://github.com/elianap/LACE).

## Paper

[Eliana Pastor and Elena Baralis. 2019. Explaining black box models by means of local rules.](https://doi.org/10.1145/3297280.3297328) In *Proceedings of the 34th ACM/SIGAPP Symposium on Applied Computing* (*SAC '19*). Association for Computing Machinery, New York, NY, USA, 510–517. 



----

# X-PLAIN

We integrate LACE in an interactive tool that allows human-in-the-loop inspection of the reasons behind model predictions. Its support for the local analysis of individual redictions enables users to inspect the local behavior of different classifiers and compare the knowledge different classifiers are exploiting for their prediction. The interactive exploration of prediction explanation provides actionable insights for both trusting and validating model predictions and, in case of unexpected behaviors, for debugging and improving the model itself.

## Video


[![Watch the video](https://raw.githubusercontent.com/lacexplain/lacexplain.github.io/main/img/x-plain-demo-video.png)](http://bit.ly/X-PLAIN-Demo-SIGMOD2020)


## Source code

The source code is available at the following [link](https://github.com/elianap/X-PLAIN-Demo).

## Paper

[Eliana Pastor and Elena Baralis. 2020. Bring Your Own Data to X-PLAIN.](https://doi.org/10.1145/3318464.3384710)  In *Proceedings of the 2020 ACM SIGMOD International Conference on Management of Data* (*SIGMOD '20*). Association for Computing Machinery, New York, NY, USA, 2805–2808.


