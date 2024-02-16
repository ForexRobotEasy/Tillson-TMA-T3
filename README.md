# Tillson TMA T3 Indicator ReadMe File

This ReadMe file provides a brief overview of the Tillson TMA T3 Indicator code. The Tillson TMA T3 Indicator is designed to calculate the Low R2 and High R3 values, generate trading signals, and forecast the price range. This code is not developed by ForexRobotEasy, but it is shared as a sample code that can work as described in the Tillson TMA T3 Indicator.

## Usage
The Tillson TMA T3 Indicator code is designed to be used in the MQL5 trading platform. It calculates the Low R2 and High R3 values based on the input parameters: Price, Highest Price (High), and Lowest Price (Low). It then generates trading signals and forecasts the price range based on these calculations.

## Inputs
The code includes the following input parameters:
- Price: The price (P) used for calculations.
- High: The highest price used for calculations.
- Low: The lowest price used for calculations.

## Functions
The code includes the following functions:

### CalculateLowR2
This function calculates the Low R2 value based on the Price, High, and Low parameters. It multiplies the Price by the difference between the High and Low values.

### CalculateHighR3
This function calculates the High R3 value based on the High parameter. It squares the High value using the MathPow function.

### GenerateTradingSignals
This function implements the logic to identify potential market turning points based on the Low R2 and High R3 values. It compares the Low R2 value with the High R3 value and generates buy or sell signals accordingly.

### ForecastPriceRange
This function uses the Low R2 and High R3 values to forecast the lower and upper limits of the price range. It prints the forecasted price range, including the lower and upper limits.

### OnTick
This function is called on every tick and serves as the entry point of the code. It calculates the Low R2 and High R3 values, generates trading signals, and forecasts the price range.

## Product Description
Tillson TMA T3 Indicator is a powerful tool designed to assist traders in identifying potential market turning points and forecasting price ranges. It calculates the Low R2 and High R3 values based on the input parameters and generates trading signals accordingly.

To use the Tillson TMA T3 Indicator, simply input the required parameters (Price, High, and Low) and attach the indicator to your desired chart in the MQL5 trading platform.

With the Tillson TMA T3 Indicator, you can easily identify buy and sell signals based on the comparison of the Low R2 and High R3 values. The indicator will generate a buy signal when the Low R2 value is greater than the High R3 value, and a sell signal when the Low R2 value is less than the High R3 value. Additionally, the indicator provides a forecasted price range, including the lower and upper limits.

Please note that ForexRobotEasy is not the official developer of the Tillson TMA T3 Indicator. We are only providing sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 platform.

For more detailed reviews and trading results of the Tillson TMA T3 Indicator, please visit [here](https://forexroboteasy.com/forex-robot-review/tillson-tma-t3-review-unveiling-the-low-r2-and-high-r3-formula/).
