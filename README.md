# environment-ministry-scraper (Paraguay)

This project is a Python scraper that helps journalist to collect environmental transaction data from the Paraguayan Ministry of Environment (MADES) portal.

The data is extracted from: https://apps.mades.gov.py/siam/portal/transaccion


The script queries a paginated JSON endpoint exposed by the MADES portal. Each request retrieves 10 records at a time.


## Output

A structured DataFrame containing all transaction records available from the portal.
