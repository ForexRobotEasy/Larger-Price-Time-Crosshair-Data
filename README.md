# Larger Price Time Crosshair Data

This code is a customizable indicator for MetaTrader 4 (MT4) that displays larger price levels and time scale on the chart. It allows users to hide the default MT4 price and time scale, display horizontal lines at specified price levels, automatically round prices, and show bid and ask prices separately.

## Features

1. Customizable Price Scale
   - The option to hide the default MT4 price scale.
   
2. Display Horizontal Lines
   - Horizontal lines are displayed at specified price levels.
   - Specified price levels: 1.20000, 1.21000, 1.22000.
   
3. Round Numbers
   - Automatic rounding of prices.
   - Options for rounding:
     - Multiples of 5
     - Multiples of 10
     - Multiples of 20
     - Multiples of 25
     
4. Fixed Count Per Window Height
   - Fixed count of price levels displayed per window height.
   - Default count: 10.
   
5. Fixed Pixel Spacing
   - Fixed pixel spacing between price levels.
   - Default spacing: 75 pixels.
   
6. Separate Bid and Ask Display
   - Option to show bid and ask prices separately.
   - Bid and ask prices are displayed with tags.
   - Tag size: 10 pixels.
   
7. Customizable Time Scale
   - The option to hide the default MT4 time scale.

## Usage

1. Install the indicator in the 'Indicators' folder of your MT4 installation directory.
2. Attach the indicator to the chart of your choice.
3. Customize the indicator settings according to your preferences.

## How It Works

The indicator uses the `OnTick()` function to access and process trading data. The code for accessing and processing trading data should be added to this function. It allows users to perform any necessary calculations or operations on the trading data.

## Product Description

The Larger Price Time Crosshair Data indicator is a powerful and customizable tool for traders using MetaTrader 4. With its advanced features, it provides a more detailed and informative chart display, helping traders make better trading decisions.

By hiding the default MT4 price and time scale, the indicator allows traders to focus on the most important information on the chart. The display of horizontal lines at specified price levels provides a visual reference for key support and resistance levels.

The automatic rounding of prices based on user-selected options (multiples of 5, 10, 20, or 25) simplifies the analysis of price movements and makes it easier to identify important price levels.

The fixed count per window height feature ensures that a consistent number of price levels are displayed on the chart, regardless of the zoom level. This allows for easier comparison of price levels across different time frames.

With the separate bid and ask display, traders can see the current bid and ask prices separately, enabling a more accurate analysis of market conditions. The bid and ask prices are displayed with tags, making them easily distinguishable.

The customizable time scale feature allows traders to hide the default MT4 time scale, providing a cleaner and less cluttered chart view.

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [this link](https://forexroboteasy.com/forex-robot-review/larger-price-time-crosshair-data-in-depth-forex-software-review/).
