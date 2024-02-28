# WH DrawFib Pro MT4 Code Development

This repository contains the code for WH DrawFib Pro, a Forex trading tool developed by Forex Robot Easy Team from forexroboteasy.com. This code enables the automatic drawing of Fibonacci retracement levels on the chart and provides a user-friendly interface for traders to modify these levels based on their strategies.

## Global Variables
- `fibLevels[]`: An array to store modified Fibonacci levels.

## Function Descriptions

### CalculateFibonacciLevels(int start, int end)
This function calculates Fibonacci retracement levels based on the specified start and end points. The calculated levels are then stored in the `fibLevels` array.

### DrawFibonacciLevels()
This function draws Fibonacci retracement levels on the chart using the calculated Fibonacci levels from the `fibLevels` array.

### ModifyFibonacciLevels(int level, int value)
This function allows traders to modify specific Fibonacci levels by providing the level and desired value. The modified levels are updated in the `fibLevels` array.

### HandleUserInput()
This function handles user input by prompting them to specify the Fibonacci level and value they wish to modify. It then calls the `ModifyFibonacciLevels` function with the provided input.

### OnStart()
The main function of the program, `OnStart()`, controls the program flow. It first calculates the Fibonacci levels using the specified start and end points, then draws these levels on the chart. Finally, it handles user input to modify the Fibonacci levels.

Note: ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work as described in the WH DrawFib Pro MT4 product. For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/wh-drawfib-pro-mt4-review-unbiased-analysis-real-results/). To find the official developer of this product, please refer to MQL5.
