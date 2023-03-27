# Tibber Power-BI-Report 

This repository contains a Power-BI-Report designed to evaluate the consumption and costs for Tibber customers. It is aimed at Tibber customers who have a personal access token from https://developer.tibber.com and Microsoft's "Power BI Desktop" installed.

## Requirements
- Tibber customer account
- Microsoft's "Power BI Desktop" installed (available for free on Microsoft Store)
- Personal access token from https://developer.tibber.com

## How to Use
1. Clone or download the repository
2. Open the `tibber.pbix` file with Power BI Desktop
3. Click on "Transform Data" in the start menu 
4. Click on "Edit Parameters"
5. Enter your Tibber access token
6. Save and close the parameter editor
7. The report will automatically refresh with your data

## Features

### Current Prices 
Displays the current prices for electricity consumption including the following day, if already available. A useful additional feature is the ability to show the average price for variable time periods. For example, if you need to charge your car for about 5 hours, select "5" as the time span, and the chart will display the average price for the next 5 hours at each start time.

### Consumption and Costs 
Displays the consumption and effective cost for each time period over the last 7, 30, or 365 days. 

### Cost Comparison
Displays the actual cost incurred versus the cost that would have been incurred at the average Tibber price. If the actual cost is lower than the Tibber average price, it means that the user was successful in scheduling electricity consumption during low-cost periods. The "SLP costs" show the cost that would have been incurred if the consumption was based on the standard consumption profile.

### Comparison with Alternative Providers
Displays a comparison between Tibber and alternative electricity providers. The user can enter the price they would have paid with another provider, such as the local utility or the previous provider, for the same consumption pattern.

### Average Price per Consumption
Calculates the average price per hour for high and low consumption periods. The comparison values include the user's average price, Tibber's average price, and the average price based on the standard consumption profile.

### Statistical Data
Displays the user's realized labor price, consumption, and cost for the selected time period and per day, as well as the predicted annual values based on the standard consumption profile.

## Support and Feedback
For questions and feedback, please contact the repository owner. Enjoy!
