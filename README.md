# Juan DOE 

2021 (c) Diego Salgado, under MIT License.

This program is a search engine for publications of company statements in the Electronic Official Gazette of Chile (Diario Oficial Electrónico, "DOE").

It consists of the following modules:

* A scraper module that collects publications from August 17th, 2016 to date in a database (to define if it will be saved in CSV or in SQLite).

The scraper module, which we will call "theHound", will enter the site, it will check if there is an edition on that day, and then, if there is more than one edition on that day (I have seen up to 4).

* A module that updates the database on the day the program is opened.

* An offline search module, which searches the database and whose output is:

     1. If there are publications of the company.
     2. The dates of the publications.
     3. What does it correspond to: constitution, modification or dissolution.
     4. Link to download the extract.
