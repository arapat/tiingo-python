=======
History
=======

0.13.0 (2019-11-XX - Unreleased)
--------------------------------
* Minor: Address Pandas Future Warning for sorting in pd.concat (#392)
* Feature: Add option to request data in csv format in get_dataframe method potentially boosting speed up to 4-5x. (#523)

0.12.0 (2019-10-20)
--------------------
* Feature: Added 3 new methods for crypo endpoints: top of book prices, historical, and metadata endpoints (@n1rna #340)
* Feature: Permit list_tickers to support multiple asset types at once (@n1rna #346)

0.11.0 (2019-09-01)
--------------------
* [/news] Internally rename sources parameter to "source", ensure lists are passed as comma separated values #325. Non-breaking external change.
* [/news] Add new URL parameter for "onlyWithTickers" #327

0.10.x (2019-05-11)
--------------------
* Documentation: Added a "Peer Comparison Analysis" Jupyter Notebook under "/examples" (@i3creations #197)
* Minor: Update error message to clarify multiple tickers only work with single metrics
* Updated development dependencies

0.9.x (2019-01-30)
------------------
* Documentation: Added runnable jupyter notebook sample under "/examples"
* Minor: bumped various library dependencies

0.8.0 (2018-07-06)
------------------
* Major: Add IEX Endpoint to retrieve data with intraday frequencies (@dcwtx #125)
* Minor: update documentation for contributing/releasing new versions
* Speed up Travis build process with pip cache

0.7.0 (2018-06-14)
------------------
* Major: Provide functions for returning data as pandas Dataframes or Series (@dcwtx #112)
* Minor documentation edits

0.6.0 (2018-04-30)
------------------

* Fix bug in resample argument name (@dcwtx #82)
* Add tool for removing API Keys from test fixtures (@dcwtx #107)
* Remove official support for Python 3.3

0.5.0 (2018-03-11)
------------------

* Updated examples in docs for getting historical prices
* Add interfaces to obtain mutual fund and ETF tickers (@savagesmc #62)
* Raise explicit error when API key is missing (#44)
* Update development dependencies


0.4.0 (2017-10-22)
------------------

* Make tests run in 1/10th the time with ``vcr.py`` (@condemil #32)
* Add support for returning python objects instead of dictionaries (@BharatKalluri #33)


0.3.0 (2017-09-17)
------------------

* Add support for listing all tickers + date ranges
* Add support for interacting with the ``/news`` API
* Improve logging of REST client errors


0.2.0 (2017-09-01)
------------------

* Improve test coverage of tickers endpoint
* Deprecate the Mutual Funds endpoint

0.1.0 (2017-08-24)
------------------

* First release on PyPI.
