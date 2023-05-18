# Recbaselines2023

## Dataset description

This dataset describes baseline models used for comparative experiments in papers on different types of recommender systems. The pre-processed version consists of 903 papers and 363 baseline models, with 5467 interractions between them. The dataset includes "paper - baseline model" interractions and additional data for each paper, such as the web link to a paper, the title of the paper and the year of publication. You can find the file [here.](share/data/before_preprocessing.csv)

The data were collected from [Google Scholar](https://scholar.google.com/). The collected articles were published between 2010 and 2022. The dataset will be updated as new papers are published. If you find any inconsistencies or would like your paper to be included in the dataset, please contact us.

Each row of the dataset consists of following collumns:

| Column    |             Description             |                             Example                             |
| :-------- | :---------------------------------: | :-------------------------------------------------------------: |
| Paper_id  |     Unique paper identification     |                                1                                |
| URL       |         WEB link to a paper         |              https://arxiv.org/pdf/1809.07053.pdf              |
| Title     |             Paper title             | NAIS: Neural Attentive Item Similarity Model for Recommendation |
| Year      |        A year of publishing        |                              2018                              |
| Baselines | List of used recommender algorithms |                        MF;MLP;FISM;NAIS                        |

## Preprocessed dataset statistics

| Number of papers | Number of models | Number of interactions | Density |
| :--------------: | :--------------: | :--------------------: | :-----: |
|       903       |       363       |          5467          |  1.6\%  |
