## EXPERIMENT DATA SUPPORTING THE IDENTITY-LINK-NETWORK METRIC

This git repository provides access to the data generated for the validation experiments of the Identity Link Network approach as described in the paper submitted at ISWC 2018 (under review). It is composed of two folders, one for each experiment (Experiment-1 and Experiment-2) with the following content:
- The matching results (folder)
- The resulting clusters and plots (folder)
- The evaluations scores (folder)
- The (subset) resulting clusters and plots selected for the domain expert's evaluation (folder)
- The evaluations scores given by the domain expert (folder)
- The resulting expert's correction (file)


## Matching results
The matching result folder contains all candidate-sets (linksets and lenses) generated using the alignment methods described 
in our submitted paper. Each candidate-set is represented using three files:

- The **main file** is a `.trig file` ([example](https://github.com/alkoudouss/Identity-Link-Network-Metric/blob/master/Experiment%202/1%20Matching-Results/idea_1e6448/linkset_1_1.trig)) that contains the **set of candidate links** in a **named graph**.
- The **generic metadata** of the candidate set is a `.sparql file` ([example](https://raw.githubusercontent.com/alkoudouss/Identity-Link-Network-Metric/master/Experiment%202/1%20Matching-Results/idea_1e6448/linkset_1_general_meta_1.sparql)) that contains generic contextual information. Running this sparql query would load the data into the **default graph**.
- The last file is a **triple level metadata** `.sparql file` ([example](https://raw.githubusercontent.com/alkoudouss/Identity-Link-Network-Metric/master/Experiment%202/1%20Matching-Results/idea_1e6448/linkset_1_singletons_1.sparql)) that contains the singletons metadata.  Running this sparql query would load the data into a **named graph**.


## Resulting clusters and plots
This folder groups the generated clusters per cluster-size. For a cluster of a given size, a .pdf file shows a plot of the cluster ([example](https://github.com/alkoudouss/Identity-Link-Network-Metric/blob/master/Experiemnt%201/2%20Clusters-and-Plots/7_Analysis_20180216/union_Eter_2014_LeidenRanking_2015_Grid_20170712_H2020_Orgref_20170703_Orgreg_20170718_P1768695787/7_N941807872/cluster_N941807872.pdf))  while a .txt file provides detailed information on the particular cluster ([example](https://raw.githubusercontent.com/alkoudouss/Identity-Link-Network-Metric/master/Experiemnt%201/2%20Clusters-and-Plots/7_Analysis_20180216/union_Eter_2014_LeidenRanking_2015_Grid_20170712_H2020_Orgref_20170703_Orgreg_20170718_P1768695787/7_N941807872/cluster_N941807872_20180216.txt)) .

## Evaluations scores
This folder contains the automatically computed **metric quality scores** further manually validated by a **non domain expert** ([example](https://raw.githubusercontent.com/alkoudouss/Identity-Link-Network-Metric/master/Experiemnt%201/3%20Cluster-Score-Sheets/5_ClusterSheet_20180216.txt)).

