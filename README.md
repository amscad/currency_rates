== README

Currency exchange rate comparator and loader.

* Currency rate loader
Import currency rates once per date.  The currency rate loader must not run a second time for a specific date, if it has previously been run before on that date.
The source of data is in EUR, but the base rate should be set to USD.

1. Read the currency data feed: http://www.ecb.europa.eu/stats/eurofxref/eurofxref-daily.xml
2. Parse the output.
3. Store the values from the run in a DB, using a model of your design.


* Webapp

1. Allows the user to search for all exchange rates for all currencies on a specific date.

2. Allow the user to select a source and target exchange rate, a date and a source amount. Using these parameters perform a conversion for the given parameters on that date.

3. Allow the user to edit all exchange rates on a given date – thus giving them the option of overriding the rates that were downloaded.

4. Allow the user to select 2 currencies and a date range and then show them the historical exchange rates for those 2 currencies in order to get a feel for how a currency is performing, compared to other currencies


To Be Completed

* Ruby version : 2.0.0

* System dependencies : Rails 4

* Configuration :

* Database creation :

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


