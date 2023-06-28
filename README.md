These materials are (or will be) a computationally reproducible version of the paper:

Lee, Meins & Larkin (2023). Parental Mentalization Across Cultures: Mind-mindedness and Parental Reflective Functioning in British and South Korean Mothers.

The file manuscript.Rmd is an R markdown file that will perform all analyses and table creation, and produce a pdf version of the manuscript.

The full repository can be downloaded (cloned), and contains all the required data files. 
However if any data files are missing the code will attempt to download them from the OSF repository for this project:
http://doi.org/10.17605/OSF.IO/MPN95

The 'docker' directory contains a Dockerfile and instructions for making a local computationally reproducible version of the analysis. In addition, the Docker environment is set up to run automatically on a remote server via Github Actions, each time a change is made (i.e. on a 'commit' to the repo). The output document is then posted back to the main repository (manuscript.pdf). If you want to make changes to the analysis and have these build automatically, you can fork the repository into your own account.

Production of the reproducible version of this manuscript was supported by an Enhancing Research Culture award from [Research England](https://www.ukri.org/councils/research-england/).

![autobuild](https://github.com/yl2944/parental-mentalization-across-cultures-/workflows/autobuild/badge.svg)
