There was a discrepancy between PC names in the map and data, I corrected that manually using a lookup table in Excel. Check data/ for the file. In hindsight, I should have used the ST_CODE and PC_CODE

Downloaded data from MyNeta archive
https://github.com/datameet/india-election-data/tree/master/affidavits

Converted CSV to correct format with Powershell

> PS C:\Code\knowYourMP\data> import-csv .\affidavits2014.csv | export-csv .\affidavits20141.csv -NoTypeInformation -Encoding UTF8