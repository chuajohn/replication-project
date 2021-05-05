# replication-project

This folder contains the materials I used for my replication of McConnell et al. (2017). Included in this folder are a number of files. The "analysis" folder contains the raw data, namely the survey data for Experiment 1 and Experiment 2 titled "data_study1_new.csv" and "data_study2_new.csv" respectively. Apart from that, Replication.rmd is the R Markdown file used to generate my replication report, and the full replication report can be found in Replication.pdf. The dataset and a number of accompanying scripts were generously provided by the original authors in a Dataverse folder, accessible here: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/R3GZZW

Replication.rmd can be run in R after downloading this directory from Github. It will load the two survey datasets in the "analysis" folder and produce Replication.pdf after being knit.

I am using Version 1.3.1073 of R Studio on macOS. My Rmd file relies on stargazer (5.2.2) and tidyverse (1.3.1) libraries.

