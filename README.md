# Causal Discovery

## Folder structure

please leave the folder structure of data and plots by all means necessary as it is accessed by all functions that save data or load data for plotting

the structure is always /dataset/subset

whenever a new subset is to be created, sub-folders must be created as well so that the functions run

### data

INPUT:

this folder has both the data in various n as well as the ground_truth saved as .csv

### plots

OUTPUT:

this folder has everything that is being generated.

#### adj_matrix

.png of the calculated adj_matrix as heat map

#### adj_matrix_comparison

.png of the calculated adj_matrix as heat map next to the ground_truth as heat map

#### adj_matrix_csv

.csv of the calculated adj_matrix for plotting

#### graphs

.png of the ground_truth. Left as a graph, on the right as a heat map

#### results

.png of the created plots for usage in the paper

## Workflow

[Depreciated] Experiments.ipynb has included data set generation and was previously used to also run tests and plotting (results) in. 

NOW:

GraphDataGeneration.ipynb handles graph building and data fitting via IIDSimulation

tests.ipynb handles testing

test_results.csv is an overview of all test results. ongoing list, can be filtered by timestamp

results.ipynb handles graph building etc for analysis




'- Leo 28.06.2024