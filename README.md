# Module_5_Financial_Planning_Tools
---
This project contains two financial analysis tools. The first is a financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

The second is a financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---
## Install

This project supports python 3.7 and the following packages. 

    'pandas'
    'python-dotenv'
    'alpaca-trade-api'
    
---
## API Keys

To use this package you first need to obtain an API key. Go here to [Sign Up](https://alpaca.markets/)
    
---
## Usage

The first part is a financial planner for emergencies. It uses api calls to pull in financial data specific to the clients portfolio. It includes traditional stocks/bonds as well as crypto assets. Additionally, we make sure there is enough savings to satisfy an emergency fund. 

The second part is a financial planner for retirement. For the Monte Carlo simulation we ran 500 trials. 

![MC Simulation]("C:\Users\rsven\fintech-workspace\Challenge_5\Module_5_Financial_Planning_Tools\Starter_Code\Images\5-4-monte-carlo-line-plot.png")

The image of the Monte Carlo simulation shows the 500 possible paths of the members' portfolio.

![MC Histogram]("C:\Users\rsven\fintech-workspace\Challenge_5\Module_5_Financial_Planning_Tools\Starter_Code\Images\5-4-monte-carlo-histogram.png")

This image shows the return outcomes. The red lines indicate probability bands. 

---
## Contributor

Ryan Svendson
rsvendson@gmail.com
