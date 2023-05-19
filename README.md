# US-Sector-Trading-System
This trading system is based on Meb Faber's original research on sector rotation. For the chart below the data for the communication sector did not date back far enough for this back test so the sector was left out. 

The jupyter lab file attached to this repository is for pulling data from yfinance which is a python library that provides free market data. From there the excel file is automated to provide buy signals once data is updated. Trades are only placed at the end of the month, and assets that do not have a positive momentum read are excluded and that portion should be cash for the next month. Also, if the asset is not above it's 168 day or 8 month SMA (simple moving averge) the asset is also excluded from trading. The excel file already takes these variables into account when providing buy signals. 

*Note:
There is also a python script attached for those not interested in excel data usage. The script will automatically pull and print the top 5 momentum assets within python. 

In the future I will provide updates for the tools that are more interactive and will be rolling out a desktop application for pulling the data needed to run the excel file. Meaning that users that do not know how to use python will also have access to these tools and trading systems. 

![US_Sector](https://github.com/monicacw21/US-Sector-Trading-System/assets/101022450/a678da37-b547-4c7f-8e21-bdd496f3182c)
Source: www.portfoliovisualizer.com

Meb Faber's Research: https://mebfaber.com/white-papers/

Disclaimer:
This report is intended for informational purposes only. No content published in this report is a recommendation to buy or sell any security or instrument or a suggestion that any trading strategy is suitable for any specific person. Dash Global Analytics is not an investment advisory business. Users of these materials are urged to seek independent verification of any information found in this report and consult with their financial, legal, and tax advisors before making an investment decision. Users of this report agree to hold Dash Global Analytics harmless for any loss they may occur due to an investment or other transaction they may enter into due (partly or entirely) to the information found in this report. 
Copyright Notice All materials, including, without limitation, text, pictures, graphics and other files and the selection and arrangement thereof are copyrighted materials of Dash Global Analytics. ©2023
