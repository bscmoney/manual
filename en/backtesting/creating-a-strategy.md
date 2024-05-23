# Creating a Strategy

In this section, we will introduce how to create a strategy on our cryptocurrency exchange platform. By creating a strategy, users can define specific conditions for automated trading and backtest the strategy using historical data to evaluate its effectiveness.

#### Step 1: Log in to the Platform

First, users need to log in to our platform using their Google account. After logging in, users will be directed to the main interface.

#### Step 2: Navigate to the Strategy Creation Page

In the main interface, click the “[Get Started](https://bsc.money/chart)” option on the homepage to enter the strategy creation and backtesting interface, where you can start defining your strategy.

#### Step 3: Define Strategy Conditions

**1. Trading Direction**

Select the trading direction of the strategy; you can choose “Long” or “Short”. The trading direction determines whether the strategy will execute a buy or sell operation when the conditions are met.

**2. Set Conditions**

Conditions are composed of a left value, a comparison symbol, and a right value. Here is a detailed explanation:

**Left Value**

The left value can be basic data or technical indicators:

* **Basic Data**: Open price, close price, highest price, lowest price, trading volume, trading amount
* **Technical Indicators**: EMA, RSI, MACD, etc.

After selecting basic data, a second and a third option will appear:

* **Second Option**: Offset, Range Max, Range Min, Range Average

1. **Offset**: The number of periods to shift forward relative to the current candlestick.
2. **Range Max**: The maximum value from the previous candlestick to the specified number of candlesticks.
3. **Range Min**: The minimum value from the previous candlestick to the specified number of candlesticks.
4. **Range Average**: The average value from the previous candlestick to the specified number of candlesticks.

* **Third Option**: Number, with different meanings corresponding to the second option

1. **Offset**
   * The number represents the offset relative to the current candlestick.
   * Example: `0` represents the current candlestick, `-1` represents the previous candlestick, and so on.
2. **Range Max**
   * The number represents the number of candlesticks from the previous candlestick.
   * Example: `-7` represents the maximum value from the previous candlestick to the 7th candlestick before it.
3. **Range Min**
   * The number represents the number of candlesticks from the previous candlestick.
   * Example: `-7` represents the minimum value from the previous candlestick to the 7th candlestick before it.
4. **Range Average**
   * The number represents the number of candlesticks from the previous candlestick.
   * Example: `-7` represents the average value from the previous candlestick to the 7th candlestick before it.

**Comparison Symbol**

The comparison symbol is used to compare the left value and the right value, including:

* Cross, Cross Up, Cross Down
* Greater Than, Less Than
* Enter Channel, Exit Channel, Inside Channel, Outside Channel
* Rise, Fall, Rise %, Fall %

When selecting a channel, two input boxes will appear for the right value. When selecting rise, fall, rise %, fall %, one input box will appear to input the percentage change relative to the right value.

**Right Value**

The right value can be another left value or a fixed value. The right value is set similarly to the left value but includes an additional “Value” input box, often used for indicator judgments (e.g., RSI > 70).

#### Step 4: Set Exit Conditions

Exit conditions include take profit and stop loss conditions. Users can set take profit and stop loss percentages. When these conditions are met, the trade will automatically end.

#### Step 5: Set Trigger Conditions

Trigger conditions determine when the strategy is activated, including:

* **Only Once**: The strategy stops triggering after the condition is met.
* **Once per Candlestick**: Triggers when the condition is met before the candlestick ends, and re-evaluates with the next candlestick.
* **Once per Candlestick (at Close)**: Evaluates trigger conditions at the end of the candlestick.

#### Step 6: Set Trading Restrictions

Trading restrictions include allowing or disallowing repeated orders:

* **Allow Repeated Orders**: Places an order whenever the trigger condition is met.
* **Disallow Repeated Orders**: Does not place a new order if the previous one has not ended.

#### Step 7: Save the Strategy

After completing all settings, click the “Save Strategy” button. A modal will pop up, prompting the user to fill in the strategy title and description. After filling in, click the “Confirm Save” button. The strategy will be saved and can be viewed and edited in the strategy list.

#### Favorite Other Users' Strategies

Users can also browse strategies created by other users and click the “Favorite” button to save them for future reference and use.

#### Important Notes

Some conditions cannot be backtested. When the trigger condition cannot confirm the entry price, the backtest function will not work properly. For example, some complex condition combinations may cause the system to be unable to determine the specific entry price, making backtesting impossible.

#### Summary

By following the above steps, users can create and save a trading strategy that meets their needs on the platform. After creating the strategy, the backtest function can be used to further verify its effectiveness and stability.
