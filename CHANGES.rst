Changes
=======

0.5.2 (2021-01-27)
------------------

* Upgrade ``autoextract-poet`` to 0.2.1
* Upgrade ``scrapinghub-autoextract`` to 0.6.1

0.5.1 (2021-01-22)
------------------
* AUTOEXTRACT_MAX_QUERY_ERROR_RETRIES default value is set to 0, to account
  for backend changes in AutoExtract API

0.5.0 (2021-01-21)
------------------

* Mayor internal and API refactor. No backwards compatible.
* Support for the new ``autoextract-poet`` 0.2.0 types
* Use of the new providers interface introduced in ``scrapy-poet``  0.1.0
* ``scrapinghub-autoextract`` AutoExtract client updated to 0.6.0
* CI is moved from Travis to Github Actions
* Python 3.9 support
