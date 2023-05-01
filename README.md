# TX_wastewater_virome

## Purpose

To share code and collaborate on analyses for the TEPHI wastewater virome manuscript (May 2022 - Feb 2023 data, Houston & El Paso)

## How to get data

After cloning this repo, change to the repo directory, then:

`wget https://zenodo.org/record/7884454/files/data.zip`

`unzip data.zip`

The data files should now be in a directory called "data".



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
