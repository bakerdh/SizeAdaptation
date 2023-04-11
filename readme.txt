These materials are a computationally reproducible version of the paper:

Meese, T.S. & Baker, D.H. (2023). Object image size is a fundamental coding dimension in human vision: new insights and model. 
Neuroscience, 514: 79-91, https://doi.org/10.1016/j.neuroscience.2023.01.025.

The file sizeadaptation.Rmd is an R markdown file that will perform all analyses and figure creation, and produce a pdf version of the manuscript.

Ideally the full repository should be downloaded, as this contains the required data files. 
However if the data files are missing the code will attempt to download them from the OSF repository for this project:
http://doi.org/10.17605/OSF.IO/KTHG3

The docker directory contains a Dockerfile and instructions for making a local computationally reproducible version of the analysis. The runtime.txt file is used by mybinder.org to generate an online version of the environment that can be accessed at:
Https://mybinder.org/v2/gh/bakerdh/SizeAdaptation/HEAD

Production of the reproducible version of this manuscript was supported by an Enhancing Research Culture award from Research England.
