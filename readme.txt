These materials are a computationally reproducible version of the paper:

Meese, T.S. & Baker, D.H. (2023). Object image size is a fundamental coding dimension in human vision: new insights and model. 
Neuroscience, 514: 79-91, https://doi.org/10.1016/j.neuroscience.2023.01.025.

The file sizeadaptation.Rmd is an R markdown file that will perform all analyses and figure creation, and produce a pdf version of the manuscript.

The full repository can be downloaded (cloned), and contains all the required data files. 
However if any data files are missing the code will attempt to download them from the OSF repository for this project:
http://doi.org/10.17605/OSF.IO/KTHG3

The 'docker' directory contains a Dockerfile and instructions for making a local computationally reproducible version of the analysis. In addition, the Docker environment is set up to run automatically on a remote server via Github Actions, each time a change is made. The output document is then available [here](https://bakerdh.github.io/SizeAdaptation/sizeadaptation.pdf). If you want to make changes to the analysis and have these build automatically, you can fork the repository into your own account. This will then require a small number of changes to the repository settings, as follows:
1. In Settings: Github Actions: General: grant read and write permissions and allow Github actions to create and approve pull requests
2. In Settings: Pages choose 'Deploy from a branch', and set the branch to 'gh-pages' and '(root)'
3. Edit the URLs in this readme file by replacing 'bakerdh' with your Github username, and if also change the name of the repository if you have set it to something other than 'SizeAdaptation'

Production of the reproducible version of this manuscript was supported by an Enhancing Research Culture award from [Research England](https://www.ukri.org/councils/research-england/).

![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/bakerdh/SizeAdaptation)
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/bakerdh/SizeAdaptation)

![autobuild](https://github.com/bakerdh/SizeAdaptation/workflows/autobuild/badge.svg)