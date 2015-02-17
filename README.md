# StockAnalysisTool

Introduction:

Goal is to create a web application for analyzing investment strategies. User
creates a series of rules for selling and buying stocks, and the application
returns a rank for the investment strategy. Rank is determined as the average
return for an investment of $100, based on historical data of a series of
stocks.

Detailed Description:

* Environment (sketch to be uploaded):
  Made with Google's Polymer platform.
  Window divided in 4 panes: 
    bottom pane is a core-drawer-panel; 
    top pane is a core-toolbar.
    top-right: contains header app name and paper-tabs for navigating betweenn pages.
    top-left: contains company logo and contact.
    bottom-left: contains a list of card elements showing information on some stocks (that have been defined as user definable parameters).
    bottom-right: contains page from currently selected tab.

  (Tentative) Tabs (i.e. accessible pages):
    - Market Data
    - Simulation -> defines parameters for new simulation and starts computation
    - Analysis Results [1] -> contains results of simulation run. New tab created for every simulation ran. Limit max number of Analysis tab?
    - Analysis Results [2]
    - ...
    - Parameters -> user definable parameters related to the web app, e.g. list of stocks to show in bottom-left pane, currency for analysis, ...








Technical Details:

Web application built in HTML5, JavaScript, CSS.
Historical financial data is retrieved from  Google Finance API
as JSON through the use of Quandl.com API.
