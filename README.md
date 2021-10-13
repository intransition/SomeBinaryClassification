# SomeBinaryClassification
CONTENTS

A few pipeline examples for binary classification
(from data inception to model save).

1. Binary_Classif_v1.3.ipynb.
Protocol to train several models using Scikit-Learn algorithms together. These can be run for a selectable number of times.
Described and commented throughout, appendices include a to do list.
Stable and functioning


2. BiC_PyCaret_V1.1.ipynb.
Protocol to train several models using the pyCaret library – with a few more algorithms (including xgbost and catboost with respect to nbook above.
Modified/extended version with respect to the one provided by the pyCaret docs. 
Described and commented throughout, appendices include a to do list.
Functioning, but a few issues remain, possibly related to library versions. 
UPDATE: previous runs with two different pre-existing environments, in 3.6.3 and 3.9.6 python, gave errors - though not blocking - possibly due to incostintent libraries. Once an ad-hoc epycaret env was created (as per included .yml file) no further errors were encountered.
