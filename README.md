# protist_id

A machine learning project in which I automate protist species identification.
Based off a problem I tackled in a [research project](https://doi.org/10.1098/rspb.2022.0543) for which I had to count and identify unicellular organisms from video data.
I showcase how to benchmark different algorithm to reach more than 99.5% accuracy (compared to a ~80% accuracy for human identification).

You can find a rendered version of the jupyter notebook on my [personal site](https://c-saade.github.io/projects/species_id/). 

Contents:
 - **datasets/morph_data_tXXX.csv**: training datasets in the form of CSVs where each line represents a single individual and its properties.
 - **Automated_species_id.ipynb**: a jupyter notebook to conduct the benchmarking, from data cleaning to model testing.

