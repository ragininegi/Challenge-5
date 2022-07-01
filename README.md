# Financial Planning of Emergency and Retirement

In this analysis we have determine the current value of a member’s cryptocurrency wallet, member’s stock and bond holdings to see  whether it can be used for emergency fund account or not.

For retirement planning analysis,we have use the valuations for the cryptocurrency wallet and for the stock and bond portions of the portfolio to determine if the credit union member has enough savings to build an emergency fund into their financial plan. This analysis provides a probable estimate of retirement as early as after 10 years or as late as after 30year, based on stock and bonds weightage using monte carlo simulation.


----------

# Technologies
It supports Python 3.7 and above and has been constructed in the jupyter lab notebook named financial_planning_tools.ipynb Additionally, the following packages/libraries are used to run the analysis:

- [pandas](https://pypi.org/project/pandas/) - for analyzing data
- [dotenv](https://pypi.org/project/python-dotenv/) - for loading variables from .env files
- [alpaca SDK](https://pypi.org/project/alpaca-trade-api/) - for interacting with Alpaca API for stock/bond prices
- [MCForecastTools](https://pypi.org/project/mc-simulation/) - for carrying out monte carlo simulations


-----------

## Installation Guide

Install the following dependencies:

```python
  pip install pandas
  pip install jupyterlab 
  conda install -c anaconda requests
  conda install -c jmcmurray json
  pip install python-dotenv
  pip install alpaca-trade-api

```
---

## Usage

To view the analysis, navigate to the file named ```financial_planning_tools.ipynb``` notebook in the [repository directory](https://github.com/Summi-Khanna/Challenge-5) Or you can navigate to the live version in the jupyter lab directly opening from your terminal using the clone link in terminal.

An API key and Secret Key from [Alpaca](https://app.alpaca.markets/brokerage/new-account/overview) are both required for running this jupyter notebook locally.

---

## Contributors
Ragini Negi  
Email : snegiragini16@gmail.com 
LinkedIn:https://www.linkedin.com/in/ragininegi/

---

## License

Apache 2.0
