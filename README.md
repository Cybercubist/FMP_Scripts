# FMPScripts
**The task:** to write a script which will easily load useful information about stocks list in excel-file sample. For that purpose you can use Financial Modeling Prep API (Starter Plan).

**The solution:** We wrote a script, which fills excel-samples with financial data from FMP API in one click. It should be very useful for market analysts.

In Excel-samples we decided to represent next data: <i> company name, current stock price, daily price change, weekly price change, monthly price change, change in 3 last months, market cap, enterprise value, revenue last 12 months, net income last 12 months, company industry, company decription. </i> 

That data should be useful for companies of any industry, size and type. That's why it all in our samples.

The script works pretty fast, downloading <ins>~1 asset data in 1 second</ins>. The code there is very simple, so some changes in samples are possible (if needed). Clear architecture of the script allows users to add some new sources of data, if FMP isn't appropriate for some reason.
