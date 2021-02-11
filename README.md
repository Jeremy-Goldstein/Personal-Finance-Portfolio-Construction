# Personal Finance: Portfolio Construction with Factor Tilts

## Motivation

Until relatively recently, investors had few options as well as mechanisms for purchasing fixed income and equities in their investment portfolio. However, with the proliferation of low-cost retail brokerages, the "ETF/index revolution", and breathroughs in data-driven financial research, investors today have several strategies and thousands of funds available when constructing their portfolio. With greater consumer choice though, gives rise to a new issue: Especially for those beginning to invest, it can be difficult to choose the best fit for one's level of financial literacy and specific situation. 

The main choices include: one-decision asset allocation i.e. "Target Date" funds, robo-advisors, and broad market indexes. With increasing complexity, comes greater personalization, tax efficiency, and fee management—ultimately leading to higher expected returns. The goal of this project, then, is to help manage the increasing complexity for DIY investors by using a dynamically-updating, accessible Google Sheet. The spreadsheet is customizable, but is already populated with broad-market indexes that implement a low-cost, globally-diversified portfolo tilted toward Fama-French research factors and momentum.

## Spreadsheet Usage

All cells that dynamically adjust to user input are locked, meaning a warning will appear if they are changed. In other words, the spreadsheet is set up so that users only have to input information unique to their situation, outlined below. Be aware that functionality may be disrupted should you choose to modify other cells, but doing so is encouraged: All formulas use Named Ranges (referring to cells by variable-like names instead of by cell column/number) to make modifications easier.  

* Access the spreadsheet [here](https://docs.google.com/spreadsheets/d/1Sl32vNc95Agf1k2oQp6iBLzTQxWHLeMlYLO7PUxcIds/edit?usp=sharing) and make a copy saved to your Google Drive to enable editing
* Replace the example values in the grey cells from rows 20-22:
  * Portfolio Goal
  * Factor Tilt
  * Behavior Tilt
  * Risk Tolerance
* Replace any example Ticker with another ETF, mutual fund, stock or cryptocurrency, and the other columns will automatically update
* Switch to the second sheet "Portfolio: Balance" and input the units owned of each security
* Visit portfoliovisualizer.com using the Direct Analysis links to get detailed information about your current portfolio; note that any change to Tickers or Target Portfolio will automatically be reflected in these links
* Toggle the checkboxes to view the balances in different accounts, using the Error in Balance column to understand how to rebalance 
* Hover over several cells for more detailed explanation of equations used and current technical limitations  
