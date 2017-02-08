# AdventureWorks for Postgres

This is based off the work done by [lorint](https://github.com/lorint/AdventureWorks-for-Postgres). We've already done the work to convert the csv's to be compatible with postgres. If you would like the original files, head over to [Adventure Works 2014 OLTP](https://msftdbprodsamples.codeplex.com/downloads/get/880662) download page. The download includes a script for loading the data into MSSQL Server.

## Getting started

First, make sure you have postgres installed. You can do this by typing `psql` in terminal.  
If nothing comes up, install postgres using `brew install postgres`. This will install and initialize a postgres database.

### Windows

Head over to [https://www.postgresql.org/download/windows/](https://www.postgresql.org/download/windows/) and follow the instructions.

### Run the script

Once you have confirmed your postgres install, run the following two lines:

	psql -c "CREATE DATABASE \"Adventureworks\";"
	psql -d Adventureworks < install.sql

You're all set!