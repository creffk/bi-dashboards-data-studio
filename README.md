# bi-dashboards-data-studio

I have setup a series of tables and dashboards inside of Google Data Studio that show our progress towards our copmany goal, the breakdown into operations objectives and broken down even further to our progress for our client services teams towards their performance incentives.

Most of our initiatives we're tracking include a clause of "... in a year", so most of our dashbaords have a timeseries element that is tracking a rolling 12 month window from the previous month through the 12 months prior. Why wait for January to undrerstand how we're doing? Also sometimes there are data tables of historical data to give more than point data for a given month.

The data is collected both manually and dynamically out of Quickbooks, our proprietary CRM, a 3rd Party Vendor CRM, Google Ads platform and data aggregations in local csv files. Most of the data is warehoused as both Google Sheets and BigQuery tables for simple syncing into Data Studio and for fast querying via SQL. 

The methods aren't yet proven to be vital to our company, and the addage of premature optimization as the root of all evil has been employed. Once it's clear that there is buy-into the methods and automation is necessary, I'll look into automating the ETL and storage into a Lake possibly. But now it's not necessary.
