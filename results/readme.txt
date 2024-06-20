The results of the experiments (with the MUTAG dataset) can be found here after running app/GEDExperiments.
For the results with the other datasets, download datasets "MSRC_9", "NCI1", "Letter-med", and "PTC_FM" and adjust the variables allDatasets, datasets and dss accordingly (see code comments).

allExperiments() can be adjusted to run the experiments for different parameter choices.

In this folder, after running the experiments, the following files can be found:

DS = name of dataset


DS_pairs.txt: Stores the indices of the randomly chosen graph pairs

approximation_results.txt: for each dataset and method/parameter choice the average approximation error

runtime_results.txt: for each dataset and method/parameter choice the average running time for computing the approximation

DS_approxResults.txt: The values (method1, method2) ready for the scatter plot for comparison

Other files simply store the approximation results for the different methods (g1_ID g2_ID value), so they have to be computed only once.

