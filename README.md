# Forex Wizard Expert Advisor

Forex Wizard is an Expert Advisor (EA) developed by the Forex Robot Easy Team. This EA is designed for professional forex traders and aims to automate trading decisions based on a specific algorithm.

## Features

- Automatic lot size calculation based on the minimum deposit
- Recommended lot size is printed in the terminal
- Ability to add custom trading functions
- Close all open positions function
- Proper initialization and deinitialization of the EA

## How it Works

### Initialization

In the `OnInit()` function, the minimum deposit is retrieved using the `AccountInfoDouble()` function. Based on the deposit amount, the lot size is calculated. If the deposit is greater than or equal to 400, the lot size is set to 0.1, otherwise it is set to 0.01. The recommended lot size is then printed in the terminal.

### Trading Algorithm

The main trading algorithm is implemented in the `OnTick()` function. This function is called on each tick of the market. You can add your own trading algorithm here to execute trades based on your strategy.

### Closing Positions

The `CloseAllPositions()` function is responsible for closing all open positions. You can add your own code here to close positions based on your trading rules.

### Deinitialization

In the `OnDeinit()` function, any necessary cleanup code can be added. This function is called when the EA is being deinitialized. In this code, a message is printed in the terminal to indicate that the Expert Advisor has been deinitialized.

## Product Description

Forex Wizard is an Expert Advisor developed by the Forex Robot Easy Team. This EA is designed for professional forex traders who want to automate their trading decisions. It comes with a set of features that can help traders streamline their trading process.

The EA automatically calculates the lot size based on the minimum deposit, ensuring that appropriate risk management is maintained. The recommended lot size is printed in the terminal, providing traders with a clear understanding of the trade size.

Traders can customize the EA by adding their own trading functions. This allows them to incorporate their unique strategies and indicators into the trading algorithm.

Forex Wizard also provides a function to close all open positions. This feature can be useful for traders who want to quickly exit all positions based on certain conditions or events in the market.

Please note that Forex Robot Easy is not the official developer of this product. We are showcasing this sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Wizard Review](https://forexroboteasy.com/forex-robot-review/forex-wizard-review-expert-advisor-for-professional-forex-traders/).
