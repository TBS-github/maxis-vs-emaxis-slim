# MAXIS ETFs vs eMAXIS Slim mutual funds: which performed best?

Notebooks checking the performance of the MAXIS S&P 500 & All Country ETFs
launched in January 2020 against their mutual fund equivalents (eMAXIS Slim S&P
500 & All Country funds).

These calculations are inspired by ones on the Shintaro Money website: [S&P
500](https://shintaro-money.com/maxis-sp500-2558/) & [All
Country](https://shintaro-money.com/maxis-ac-2559/). They account for Japanese
taxes on ETF dividends and for the lag between the dividend date and the pay
date. The performance assumes you reinvest the dividends on the pay date. The
calculations are applicable for ETFs (or mutual funds) held in taxable accounts.

To run the 2559 All Country notebook, ACWI ticker data (Gross & Net) must first
be downloaded from [MSCI](https://www.msci.com/end-of-day-data-search) and
saved into a TSV file using column headers "Date	Gross	Net". I could not
find an API for this data. If anyone knows of one, please let me know.
