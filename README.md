# dbx-fitness
Using Databricks to ingest/analyze fitness data.

Rough idea is take a universal activity format (TCX? GCX?) that's in XML, parse it/load it into a medallion architecture. Make it useful, serve it up in pretty dashboards in DBSQL.

Rough project ideas:
 - Ingest historical data
	- Parse XML, load it into bronze table
 - Explore data, figure out some nice things to display
 - Implement ETL to generate gold tables
 - Build out dashboard
 - Figure out how to do batch ingest based off of fitness repo of choice (Garmin? Strava?). Make it fit the above.
