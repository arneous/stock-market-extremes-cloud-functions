#### Version 0.0.1 on https://stock-market-extremes.web.app
## Stock market extremes - App 

Here can the Firebase functions be found that are necessary to successfully setup 
[this App](https://github.com/jmandt/stock-market-extremes-ionic-app) locally.


### Getting Started

* [Download the installer](https://nodejs.org/) for Node LTS.
* Install the Firebase CLI globally: `npm install -g firebase-tools`
* Clone this repository: `git clone https://github.com/jmandt/stock-market-extremes-cloud-functions.git`.
* Run `npm install` from the project root/functions.
* Replace XXX in config_pub.json with your API KEYS
* Rename confifg_pub.json => config.json
* Login to Firebase by `firebase login` and choose your project.
* Run `firebase deploy` from the project root.

### Value Investment KPIs

## Company Analysis


##


## Financials Input required annually for Big Five (Last 10 Years)

|Name (DE)|Source|Name (EN)|Finacial Modeling Prep API| Comments |
|---|---|---|---|---|
|Summe langfristiges Fremdkapital| Bilanz (Passiva)  | Balance Sheet > Long-term Debt  | https://financialmodelingprep.com/api/v3/financials/balance-sheet-statement/AAPL  |   |
|Summe Eigenkapital   | Bilanz (Passiva)  | Balance Sheet > Total shareholders equity  |   |   |
|Summe Passiva   | Bilanz (Passiva)  | Balance Sheet > Total liabilities  |   |   |
|Umsatz   | GuV  | Income Statement > Revenue  | https://financialmodelingprep.com/api/v3/financials/income-statement/AAPL  |   |
|Operatives Ergebnis   | GuV  | Income Statement > Operating Income  |   |   |
|Steuern vom Einkommen und vom Ertrag   | GuV | Income Statement > Income Tax Expense  |   |   |
|Jahresüberschuss | GuV  | Income Statement > Gross Profit  |   |   |
|Cash flow   | Cashflow Statement  | Net cash flow | https://financialmodelingprep.com/api/v3/financials/cash-flow-statement/AAPL  |   |
|Cashflow aus der Investitionstätigkeit   | Cashflow Statement | Investing Cash Flow  |   |   |
|Ausstehende Aktien in Mio. (verwässert)  | "Wertpapierdaten"  |  Income Statement > Weighted Average Shs Out | https://financialmodelingprep.com/api/v3/financials/income-statement/AAPL  |   |
|Ergebnis je Aktie verwässert   | "Wertpapierdaten"  |   |   | Kann man auch berechnen  |
|Umsatz je Aktie   | "Wertpapierdaten"  |   |   | Kann man auch berechnen |



