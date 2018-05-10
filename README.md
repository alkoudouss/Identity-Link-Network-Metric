"# Identity-Link-Network-Metric" 

# EXPERIMENT DATA SUPPORTING THE IDENTITY-LINK-NETWORK METRIC

This git repository provides access to the data generated for the validation of the Identity Link Network approach.
The repository is composed of two folders (Experiment-1 and Experiment-2) as described in the paper submitted 
at ISWC 2018. For each folder, we provide:
- The matching results
- The resulting clusters and plots
- The evaluations scores
- The expert's cluster subset
- The expert 's score
- The resulting expert's correction

## Matching results
The matching result folder contains all candidate-sets (linksets and lenses) generated using the alignment methods described 
in our submitted paper. Each candidate-set is represented using three files

- The **main file** is a .trig file witch allows loading the **candidate-set ** as a **name graph**.
- The **generic metadata** of the candidate set is a .sparql file which loads generic contextual information into the  **default graph**.
- The last file is a **triple level metadata** .sparql file which loads the singleton metadata into a **named graph**.

## Resulting clusters and plots
This folder groups generated clusters per cluster size. For a cluster in a given cluster size, a .pdf file shows a plot of the cluster while a .txt file provides detailed information on the particular cluster.

![alt text](https://raw.githubusercontent.com/alkoudouss/Identity-Link-Network-Metric/master/Experiemnt%201/2%20Clusters-and-Plots/7_Analysis_20180216/union_Eter_2014_LeidenRanking_2015_Grid_20170712_H2020_Orgref_20170703_Orgreg_20170718_P1768695787/7_N941807872/cluster_N941807872_20180216.txt)
