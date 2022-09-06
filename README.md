# Molecular Methods in Ecology and Evolution - 2022 - UNIL Master BEE

In this repository, you will find all the informations and the data you need for the practical part of the Molecular Methods in Ecology and Evolution course. 


### repository's Architecture 

MolGen2021_Manual			- Manual with all infromations about the practicals. 

1_Frogs								- This directory contain all the data for the first project.

2_Cichlids						- This directory contain all the data for the second project.

3_Eels								- This directory contain all the data for the third project.


### Important informations

To be able to install and use all packages required, please **use R version 3.6.x. Do not use R version 4.x.x**.
If you already have an R verison installed on your laptop and want to change, you can find a way to do it [here](https://support.rstudio.com/hc/en-us/articles/200486138-Changing-R-versions-for-the-RStudio-Desktop-IDE).


### Packages installation

To install all packages required, please run these commands :

in caye you are not administrator of your computer, you can specify where the packages should be installed with the `lib` option in `install.packages()`

`install.packages("ape", dependencies = TRUE)`

`install.packages("phangorn", dependencies = TRUE)`

`install.packages("seqinr", dependencies = TRUE)`

`install.packages("adegenet", dependencies = TRUE)`

`install.packages("pegas", dependencies = TRUE)`

`install.packages("hierfstat", dependencies = TRUE)`

`install.packages("raster", dependencies = TRUE)`

`if (!requireNamespace("BiocManager", quietly = TRUE))`

`install.packages("BiocManager")`

`BiocManager::install("LEA", dependencies = TRUE)`
