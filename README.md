# AGMP: AutoGluon based multi-label prediction
AGMP was employed to predict TEMPO-catalyzed primary alcohol oxidations. Distinguished from other ML models, AGMP calssifed the reaction as reactive (Y) or non-reactive (N) at first, then output predicted yields as regression results with the new generated ‘Y/N’ descriptor.
### Files in the folder

+ ``data``
  + test: contain 1896 training data and 240 test data
  + external_test: contain 2136 training data and 1308 test data
+ ``core`` : define a multilabelpredictor
+ ``nbs``:  notebooks of AGMP
+ ``AutogluonModels``:  saved models of AGMP
### Running the code


+ model training and test : Oxidation_AGMP_main.ipynb

+ test on external_test set  : Oxidation_AGMP_external_test.ipynb

### Setup Instructions

Please install AutoGluon according to  https://auto.gluon.ai/stable/install.html.

You'll also need to pip install sklearn, numpy, pandas and matplotlib.

