"""""""""""""""""
GP Data NI Web Scraper
"""""""""""""""""

-------------------------
A web scraper for datasets in OpenDataNI https://www.opendatani.gov.uk/
-------------------------

-------
Dependencies
-------

- Poetry

-------
Install
-------

Navigate to root directory and run `poetry install`

-------
Test
-------

From root directory run `poetry run pytest`

-------
Run
-------

This web scraper works for the following url's:

- https://www.opendatani.gov.uk/dataset/gp-practice-list-sizes
- https://www.opendatani.gov.uk/dataset/gp-prescribing-data

From root directory run `poetry run python gp_data_ni_webscraper/webscraper.py "<url>"`

-------
Host
-------

This package is hosted on Gemfury: https://pypi.fury.io/pfegan415/