CKAN Data Tools
=========

A command line interface that provides access to a number of tools and services related to the Government of Canada Open Data project:

* Transformation of various GoC dataset formats
* Import data from existing GoC datasets
* Purge partial data from existing CKAN instances
* Move and update partial datasets between CKAN instances
* Test datasets and generate reports
* Facilities for working with JSON data using test proxies such as Charles

Example Use
========

Nested command structure is as follows:

$python munge.py <DATAPOINT> <COMMAND> <ENTITY> <OWNER>

For example, to delete all packages for Agriculture:

$python munge.py ckan delete pack agriculture

Complete documentation can be obtained with $python munge.py -h


