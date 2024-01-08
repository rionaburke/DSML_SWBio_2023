# Non-genetic paternal effects on offspring reproduction and health: Mechanisms and evolutionary consequences in a bird model system - Project submission for SWBio DSML module


## Introduction


This project concerns how general paternal fitness (influenced by their environment) affects how offspring develop and reproduce throughout their life. The animals are born from either high or low investment breeding lines then crossed to create hybrid offspring. The health and development of the hybrids will then be studied.

The code written for this acts as a precursor to the main project and aims to validate the selection lines by means of egg-size and lay-rate comparison between mothers (F0 generation) and daughters (F1 generation). If the lines are valid, the daughters of the purebred investment lines will be used as the mothers of the hybrid offspring for the next part.

It was built in Jupyter lab v3.6.3


## Installation


Project can be installed by downloading Jupyter notebook file along with the dataset (https://github.com/rionaburke/DSML_SWBio_2023/blob/main/simulated_quail_data_python.csv) from GitHub repository (https://github.com/rionaburke/DSML_SWBio_2023/tree/main).


## Dataset

The dataset simulated_quail_data_python consists of simulated data based on pre-existing collection parameters (see Jupyter notebook).

- Sex: The sex of the F1 bird 
- BirdID: The ID of the F1 bird 
- Mother: The ID of the F0 mother of the F1 bird
- MatLine: The breeding line the F0 mother originates from 
- Father: The ID of the F0 father of the F1 bird
- PatLine: The breeding line the F0 father originates from 
- EggsLaid: The number of eggs laid by F1 offspring 
- DaysObserved: The number of days the birds were studied for
- LayRate: The number of eggs laid divided by the number of days observed
- AverageEggF1: The average weight of the eggs laid by the F1 offspring
- AverageEggF0: The average weight of the eggs laid by the F0 mothers


## Results from initial sample dataset


From the analysis, we found that F1 offspring of both the HI and LI lines lay eggs similar in weight to their F0 mothers. We also found that HI offspring seem to lay at a lower rate than LI offspring but that LI offspring have a larger range of lay rate. F0 HI egg weight is distinct from F0 LI mother egg weight when plotted but F1 HI egg weight is not as clearly removed from F1 LI egg weight perhaps indicating confounding factors such as the environment.


## Support information


Any issues or queries can be raised by contacting rb955@exeter.ac.uk





