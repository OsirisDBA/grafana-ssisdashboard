# grafana-ssisdashboard

grafana-ssisdashboard is a faithful recreation of [Davide Mauri](http://www.davidemauri.it/)'s [HTML5 SSIS Dashboard](https://github.com/yorek/ssis-dashboard) using [Grafana](https://grafana.com/) instead of a standalone project.

## Installation
**Step 1**: Import the JSON files into your Grafana instance

**Step 2** Update the Executions table panel's ID column to point to the correct URL of your Grafana instance. It defaults to localhost.

**Step 3** Update the $Instance variable. Set the "Instance name filter" to a regular expression that returns your SSIS datasources. By default it will return any SQL Server datasources with SSIS in the name.
