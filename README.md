# Animal-Classifier
Jupyter notebook that creates and trains a model that can perform image classification based on a provided dataset with each image in that dataset belonging to a folder that's named after its class.

Currently supports 3 classes, but can support as many as wanted by editing the first cell under 'Create Dataframe for Input and Output'

Trained models are too large to upload to GitHub, but accuracy results are provided below

## Results
Model | Class | Test Accuracy (%)
--- | --- | --- 
Cat/Dog/Neither   | Cat     | 80
NA                | Dog     | 44
NA                | Neither | 61
NA                | |
Cat/Dog/Fish      | Cat     | 70
NA                | Dog     | 32
NA                | Fish    | 89
NA                | |
Cat/Bird/Fish     | Cat     | 85
NA                | Bird    | 74
NA                | Fish    | 85
NA                | |
Cat/Dog/Bird/Fish | Cat     | 85
NA                | Dog     | 27
NA                | Bird    | 76
NA                | Fish    | 77
