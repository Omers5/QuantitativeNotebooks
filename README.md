# QuantitativeNotebooks
Various Jupyter Notebooks that scan/trade stocks

alpacaprophetsingle - uses Alpaca.markets to get hourly data of a single stock for past x amount of days, feeds open prices into Facebook prophet, then predicts price for next x/10 days along with plots.

alpacaprophet - Loops through all stocks on Alpaca.markets and inputs pricing data into Facebook prophet, ranks stocks amongst other stocks based on percentage of expected move, then plots top ranked stocks
  Plan to make multithreaded since runtime is currently very long
