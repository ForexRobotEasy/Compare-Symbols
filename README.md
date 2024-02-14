# Compare Symbols Forex Software

This is a sample code for a Forex software that compares the values of multiple currency pairs (symbols) and triggers alerts if certain parameters are met. Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Product Description

The Compare Symbols Forex Software is designed to analyze the values of multiple currency pairs and provide alerts when specific parameters are met. It is a powerful tool for traders who want to monitor multiple symbols simultaneously and take advantage of potential trading opportunities.

### Key Features

- Compare values of multiple currency pairs in real-time
- Display symbol data on the chart for easy visualization
- Save symbol data to a CSV file for further analysis
- Trigger alerts when symbol values exceed predefined parameters
- Customizable parameters to suit individual trading strategies

### How it Works

1. The software includes necessary libraries for trading operations and chart object manipulation.
2. Constants and global variables are defined to store symbols and parameters.
3. Chart objects are initialized to display symbol data and parameter labels.
4. File variables are initialized to save symbol data to a CSV file.
5. Alert variables are set to enable or disable alerts and track alert triggers.
6. The `CompareSymbols` function is called to perform symbol comparison.
7. Chart objects are cleared, and the CSV file is cleared for a fresh comparison.
8. For each symbol in the list, the current and previous values are retrieved.
9. Symbol data is displayed on the chart using text objects and saved to the CSV file.
10. Symbol parameters are checked, and if a parameter is exceeded, an alert is triggered and a label is displayed on the chart.
11. The `OnInit` event initializes the trade and chart objects, creates the CSV file if it doesn't exist, and sets up alerts.
12. The `OnTick` event calls the `CompareSymbols` function to compare symbols on every tick.
13. The `OnDeinit` event displays a stop alert when the software is stopped.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/compare-symbols-forex-software-honest-review-user-ratings/).
