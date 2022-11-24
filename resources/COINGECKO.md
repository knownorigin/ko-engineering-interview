# COINGECKO

## Description

We work in crypto, and heavily use 3rd party APIs so we would like you to retrieve some crypto data from a 3rd party.

e.g., an example of the bitcoin price can be seen here -
https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&ids=bitcoin

## Exercise

### Part 1

Using the API below - Get the last 5 days’ worth of Ethereum prices.

Example API call: https://api.coingecko.com/api/v3/coins/ethereum/history?date=30-12-2017
* Coin IDs: `ethereum` / `bitcoin`
* Date is in the format `DD-MM-YYYY`
* Documentation is:
https://www.coingecko.com/api/documentations/v3#/coins/get_coins__id__history

1. Retrieve the prices for the last 5 days, including today.
   * Use either `ethereum` or `bitcoin`.

2. Returns these prices, testing the result.

### Part 2

If there is enough time, expanding on part 1, find the average weekly price for the last month.

## Notes

Things we're looking for:

* Talk us through what you’re doing and the decisions you’re making, it’s OK to think
  out loud.
* A focus on clean, testable code.
* Implement or highlight any optimisations you have identified.
* Write tests for your implementation.
