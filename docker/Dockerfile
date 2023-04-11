FROM rocker/rstudio:4.2.2

RUN apt-get update -qq
RUN apt-get -y install cmake
RUN apt-get -y --no-install-recommends install libglu1-mesa-dev
RUN apt-get -y install libxml2-dev
RUN apt-get -y install ghostscript
RUN apt-get -y install libxt-dev
RUN apt-get -y install git

RUN R -e 'install.packages("remotes"); remotes::install_version("car", version="3.1-1"); remotes::install_version("pracma", version="2.4.2"); remotes::install_version("pals", version="1.7"); remotes::install_version("grImport", version="0.9-5"); remotes::install_version("tictoc", version="1.1"); remotes::install_version("BayesFactor", version="0.9.12-4.4"); remotes::install_version("ez", version="4.4-0"); remotes::install_version("renv", version="0.16.0"); remotes::install_version("bookdown", version="0.32"); remotes::install_version("knitr", version="1.42"); remotes::install_version("markdown", version="1.5"); remotes::install_version("tinytex", version="0.44"); remotes::install_version("osfr", version="0.2.9"); tinytex::install_tinytex()'