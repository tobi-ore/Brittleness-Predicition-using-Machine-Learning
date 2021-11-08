# Brittleness-Predicition-using-Machine-Learning
## Objectives
Brittleness is known to be an important reservoir property in hydraulic fracturing. Under a certain level of differential stress, brittle rocks fail creating planes of weakness that are kept open by the injected proppant, causing secondary permeability in the rock.  This repo contains Jupyter notebooks to estimate brittleness using elastic and mineralogical properties and to predict brittleness using machine learning. The workflow is typical for any similiar project and it entails:
•	Wrangle and process the data to the desired format;
•	Carry out quick look and statistical analysis of the well log data;
•	Develop a model using a neural network, support vector regression and gradient boosting; and
•	Deploy the model and investigate its performance.


## Data Source
The geophysical logs used in this study are from the Appalachian Basin. The data is made available through the open-source subsurface data published by Marcellus Shale Energy and Environment Laboratory (MSEEL) which can be accessed via the link: https://www.mseel.com/data/Wells_Datasets/


## Implementation

__Software__: `Python`

__Packages__: `lasio`, `sklearn`, `numpy`, `pandas` and `matplotlib`

The various manipulations and operations on the well logs is done by running the jupyter notebook called `Well_Log_Editting.ipnyb` and `Well_Log_Formatting.ipnyb`. 

The `ML_Models_X.ipnyb` is the notebook where the models are built, trained and deployed.

## Authors

[Tobi Ore](https://github.com/tobi-ore) and
[Dengliang Gao]

## License

[This project is licensed under the MIT License](https://choosealicense.com/licenses/mit/)
