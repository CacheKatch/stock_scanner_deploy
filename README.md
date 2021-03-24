# stock_scanner_deploy

The stock screener developed on this repository replicates the code developed by Shashank Vemuri [1]

## Required Libraries and dependencies:

To install necessary dependencies run the following command in the folder and anvironment:
```shell
    pip install -r requirements.txt
```

## Scanner logic / conditions:

&ensp; The current price of the security must be greater then the 150 and 200 day simple moving average.

&ensp; The 150-d moving average must be greater than the 200-day moving average.

&ensp; The 200-day moving average must be trending up for at least 1 month.

&ensp; The 50-d moving average must be greater than the 150-d simple moving average and the 200-day simple moving average.

&ensp; The current price must be greater than the 50-day simple moving average.

&ensp; The current price must be at least 30% above the 52 week low.

&ensp; The current price must be within 25% of the 52 week high.

&ensp; The IBD RS-Rating must be greater than 70.

## Resources:
[1] (https://towardsdatascience.com/making-a-stock-screener-with-python-4f591b198261)

[2] (http://theautomatic.net/yahoo_fin-documentation/)
