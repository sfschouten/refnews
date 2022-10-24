# RefNews-12
This repository contains the resources necessary to use the RefNews-12 dataset.

RefNews-12 is a dataset of news articles collected from a diverse set of publications. It uses [MWEP](https://github.com/sfschouten/multilingual-wiki-event-pipeline/) to collect news articles that are linked to from Wikipedia pages.

We do not distribute the contents of the news articles directly, since this would require express permission from the copyright holder(s). Instead, we distribute a set of URIs to snapshots of the news articles on the Wayback Machine. 

 - The [`data`]() directory contains a set of binary files with the URIs and corresponding metadata.
 - The [`RefNews-LoadExisting.ipynb`]() notebook shows how to read these binary files, and download the dataset (almost) exactly as it was used for the [**Probing the representations of named entities in Transformer-based Language Models**]() paper (as presented at the [BlackboxNLP](https://blackboxnlp.github.io/) 2022 workshop).
 - The [`RefNews-DataCollectionFromScratch.ipynb`]() notebook gives example code which can be used to collect a RefNews dataset from scratch. 

 
## Citation
...