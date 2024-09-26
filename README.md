![S-PLUS Logo](https://splus.cloud/images/splus_logo_fundo_branco.jpg)

# Workshop

The content of this workshop was presented at XLVII Reunião Anual da SAB, held in Águas de Lindóia (São Paulo, Brazil)

## Requirements

- Python 3.8
- [splusdata](https://github.com/Schwarzam/splusdata) to access S-PLUS data.
- [S-Cubes](https://github.com/elacerda/s-cubes) to create IFS-like galaxy cubes
- [Jupyter](https://jupyter.org/) to run the notebooks to open the classes and exercises notebooks
- [LSDB](https://lsdb.readthedocs.io/) to deal with big catalogs
- **S-Cubes** requires [Source-extractor (*SEXtractor*)](https://sextractor.readthedocs.io/en/latest/index.html) installed either *locally* or *system-wide* (*to install with aptitude: sudo apt install source-extractor*)
- An user account at [S-PLUS Cloud](https://splus.cloud/) in order to access the necessary data.

## Installation 

To install splusdata, S-Cubes, Jupyter and LSDB, simply run:

    pip install -r requirements.txt

## About S-PLUS

[Slides](https://github.com/splus-collab/XLVII_SAB_workshop/blob/main/slides_splus_workshop.pdf)


## Tutorials

### 1. Introduction to S-PLUS

### 2. S-PLUS Data Structures
 - [Intro to splus.cloud and splusdata](content/splus%20basics/1.splus_website_and_python.ipynb)
 - [Fast query with lsdb](content/splus%20basics/2.lsdb_query.ipynb)
 - [Extinction Correction and Zero Points in Astronomical Data](content/splus%20basics/3.%20getting_zps_nd_extiction.ipynb)

### 3. Hands-on: S-PLUS data use - some science cases
 - [H.R. diagram of a cluster of stars](content/hands-on/1st_science_case_solution.ipynb)
 - [Galaxy crosmatch and a color-magnitude diagram](content/hands-on/2nd_science_case_solution.ipynb)

### 4. S-Cubes: Creating IFS-like cubes with S-PLUS data
 - [S-Cubes pdf presentation](content/hands-on/s-cubes/presentation.pdf)
 - [Creating a cube and check result](content/hands-on/s-cubes/scubes.ipynb)
