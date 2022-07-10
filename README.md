# QuantitativeNotebooks
Various Jupyter Notebooks that scan/trade stocks

alpacaprophet - Loops through all stocks on Alpaca.markets and inputs pricing data into Facebook prophet, ranks stocks amongst other stocks based on percentage of expected move, then plots top ranked stocks. Possible plan to make multithreaded since runtime is currently very long (about 2 hrs on my laptop)

alpacaprophetsingle - uses Alpaca.markets to get hourly data of a single stock for past x amount of days, feeds open prices into Facebook prophet, then predicts price for next x/10 days along with plots.
