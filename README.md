# FSSearch #

Search files indexed with FSCrawler.

This Version was tested with version 2.5 of FSCrawler, ElasticSearch
6.3.2 and Python 3.7. At least for Python other versions will
work. This program relies on the index structure FSCrawler 2.5
creates. Although this may change for other versions, not all of the
information is used, so it may work even if the index has another
format. For using this programm you must install FSCrawler and
ElasticSearch first and index your documents with FSCrawler.

# Howto use #
Install `requirements.txt`.
Just run `search.py` with a search term and submit the desired index with the --index flag.

# TODO #

