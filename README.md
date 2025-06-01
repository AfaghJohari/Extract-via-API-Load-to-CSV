# Extract-via-API-Load-to-CSV
This Power Automate solution get data via API and transform it in Jason and load it to a CSV file in 4 steps:

To test this flow the Manually trigger a flow action is added
1- Extract data from the API address(http://transport.opendata.ch/v1/stationboard?station=Aarau&limit=10) via HTTP action
2- Transform the data in Jason via Pars Jason action
3- Load the data to One drive CSV file. If the file not exist it will be created and if yhe file exists it will be replaced.
