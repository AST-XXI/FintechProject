# FinTech Project1 - Cryptara, the friendly Robo Advisor that helps investors make effective investment decisions in the Crypto Market.

## Installation
### The following API and websockets are required to run Cryptara:
    1. TVDATAFEED
    pip install --upgrade --no-cache-dir git+https://github.com/StreamAlpha/tvdatafeed.git
    2. TAHandler
    pip install tradingview-ta

    
## Trading View API runs on separate Python libraries then the Pyviz environment, thus two separate environments are needed to run the Roboadvisor and Visualization scripts. Additional information is below:

### cryptara_roboadvisor_final_STEP 1 - This is step 1 which will analyze and select the best performing Cryptos, and extract data to csv files for step 2 (visualization)
    Note: You must be connected through TVDataFeed websocket and TAHandler API to 
    run this file.
### cryptara_results_visualization_STEP 2- This script will run visualization models on the data extracted in Step 1. Ultimately an interactive dashboard is created to help support the reasoning behind Crytptara's selections.  
    Note: You must run all visualization dashboards in your Pyviz environment.
 
## Resources:
1. TradingView
https://www.tradingview.com/

2. TA Handler (Trading View API):
https://github.com/brian-the-dev/python-tradingview-ta/blob/main/docs/overview.rst

3. TV DataFeed (TradingView websocket):
https://github.com/StreamAlpha/tvdatafeed

4. Numpy
https://numpy.org/

5. PyViz
https://examples.pyviz.org/user_guide.html

    
 
    