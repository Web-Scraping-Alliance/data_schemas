Web Scraping Alliance
=====================

The objective of the web scraping alliance is to offer an industry wide standard definition of scraped items,
this will allow easy usage between companies and better integration on automated systems

This repository contains the structures of data schemas we are the result of the web scraping alliance,
and are free to use.

How the schemas are defined
---------------------------
The main purpose of defining a schema is to have an json object that can be used in many case as possible,
for example the `product` schema should be in any e-commerce website instead of having an schema per website.

To propose a new schema, it should be for information that any of the existing schemas cannot be applied to.

How to collaborate
------------------
This is an open repository, anyone can see its contents but to make a pull request one must be a member of the web scraping alliance.

The acceptance of a pull request is determined by the following rules:

* A pull request can be summited be any member of the web scraping alliance.
* Each organization that belong the Web Scraping Alliance will have a member "administrator" role for one user per member organization.
* A pull request will be merged to main branch if half plus one of all member with "administrator" role approves the pull request.
* The criteria for a pull request acceptance, is the proposed changes expand the currents schemas without redundancy of information or duplicate fields, or it propose a new schema for a new type of information that any of the existing schemas cannot cover.
* A pull request will be rejected if half plus one of all member with "administrator" role decide it.

Web Scraping Alliance Members
-----------------------------

- `Bitmaker <https://bitmaker.la/>`_