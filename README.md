# TX_wastewater_virome

## Purpose

To share code and collaborate on analyses for the TEPHI wastewater virome manuscript (May 2022 - Feb 2023 data, Houston & El Paso)

## How to get data

After cloning this repo, change to the repo directory, then:

`wget https://zenodo.org/record/7884454/files/data.zip`

`unzip data.zip`

The data files should now be in a directory called "data".

## Using renv to load the versioned libraries and run analyses in RStudio

1) If not done already, git clone this repo

2) In the Finder, double click on `TX_wastewater_virome.Rproj` to load the project in RStudio

3) use `renv` to install the necessary libraries

`renv::restore()`

## Running the analyses

With the `data` downloaded and the appropriate R packages downloaded, any of the `.rmd` files can be opened in `R Studio`.

Feel free to run the scripts in their entirety or chunk-by-chunk to reproduct the analyses.


## Directory Tree


** There is a .gitignore on the `data/` directory **


```
TX_wastewater_virome/
│   README.md
│   TX_wastewater_virome.Rproj
│
└───scripts/
│   └───virome_community/
│       │   some_scripts.Rmd
│   └───virus_variant_analyses/
│       │   some_scripts.Rmd
│   └───clinical_correlations/
│       │   some_scripts.Rmd
│   └───maps/
│       │   some_scripts.Rmd
│
└───data/
│   │   virus_abundance_table.tsv
│   │   WWTP_sample_metadata.xlsx
│   │   other_data.xlsx
│   │   etc
│
└───charts/
│   │   various_figures.pdf
│
└───environment/
    │   readme.md with package versions
```
