This directory contains the files which contain the metadata necessary to collect the news articles.

See The [`RefNews-LoadExisting.ipynb`](https://github.com/sfschouten/refnews/blob/main/RefNews_LoadExisting.ipynb) notebook for how to load their contents and scrape the data.

The files are pickled python objects with class types defined in [`mwep/classes.py`](https://github.com/sfschouten/multilingual-wiki-event-pipeline/blob/master/classes.py).

Note that rather than the actual news article contents, the `content` field contains an md5 hash of contents generated at the time we scraped the data. 
The data should be the same as it was collected from a specific snapshot from the Internet Archive’s Wayback Machine, but the md5 hash allows you to make sure of this.
