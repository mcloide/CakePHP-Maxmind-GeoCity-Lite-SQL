CakePHP-Maxmind-GeoCity-Lite-SQL
================================

SQL dumps with the tables for Countries, Regions and Cities from the GeoCityLite DB from Maxmind

It is a great alternative if you cant be querying Google API in a constant basis (example: max limit of queries reached in Google).

The structure will build up a relationship between countries, regions (states) and cities. With the country iso_code you can get to the province and finally to the city list.

For any application, caching results is suggested since the number of results can be massive.

Note
====
This was made for CakePHP structure like, but it does not means that you can't use it in any other framework or application.


[![endorse](http://api.coderwall.com/mcloide/endorsecount.png)](http://coderwall.com/mcloide)