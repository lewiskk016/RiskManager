This Expert Advisor (EA) is designed to manage risk by incorporating automatic stop loss and preventing trades from exceeding a specified leverage limit in MetaTrader5. The EA calculates lot size based on a defined risk percentage per trade and automatically places stop loss orders at a fixed distance from the entry price.
## Features

- Automatically calculates lot size based on a specified risk percentage.
- Places buy orders with a fixed stop loss distance (3 pips) from the entry price.
- Includes logic to prevent trading if the leverage exceeds a maximum specified limit.


## Usage

1. Copy the provided `RiskManagementEA.mq5` file into the "Experts" folder of your MetaTrader 5 installation directory.
2. Launch MetaTrader 5 and open the MetaEditor.
3. Compile the `RiskManagementEA.mq5` file in the MetaEditor.
4. Attach the compiled EA to a chart in MetaTrader 5.
5. Adjust the input parameters (`riskPercentage` and `maxLeverage`) according to your trading preferences and broker requirements.
6. The EA will automatically manage risk by calculating lot size, placing buy orders with stop loss, and ensuring leverage compliance.


## Parameters

- `riskPercentage`: The percentage of account balance to risk per trade.
- `maxLeverage`: The maximum leverage allowed for trading. Trading will be halted if the leverage exceeds this limit.


