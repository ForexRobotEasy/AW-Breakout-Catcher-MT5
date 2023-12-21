# AW Breakout Catcher MT5

This repository contains the code for AW Breakout Catcher MT5, an advanced forex software developed by Forex Robot Easy Team. This software is designed to identify breakout opportunities in the forex market and execute profitable trades.

## Features

- Breakout identification: The software utilizes advanced algorithms to detect potential breakout patterns in the forex market.
- Take Profit calculation: The software automatically calculates the take profit level based on the user-defined variable `takeProfit`, stop loss, and current ask price.
- Notifications: The software provides the option to enable notifications in various forms, including MetaTrader platform notifications, email alerts, and push notifications.
- Customizable variables: Users can define their own variables, such as `takeProfit`, `enableNotifications`, `enableEmailAlerts`, and `enablePushNotifications`, to customize the software according to their trading preferences.

## How it works

1. The software initializes by setting default values for the variables `takeProfit`, `enableNotifications`, `enableEmailAlerts`, and `enablePushNotifications`.
2. On each tick, the software executes the trading logic. Users can implement their own trading strategy in this section.
3. The software calculates the take profit level using the user-defined `takeProfit` variable, stop loss, and current ask price.
4. The calculated take profit level is printed to the terminal using the `Print` function.
5. If notifications are enabled, the software sends notifications to the MetaTrader platform and/or email based on the user's preference.
6. Additional trading code can be added as per the user's requirements.

## Custom functions

1. `SendNotification`: This function sends a notification to the MetaTrader platform. Users can customize this function to implement their own notification system.
2. `SendMail`: This function sends an email notification. Users can customize this function to integrate their own email notification system.

Please note that ForexRobotEasy is not the official developer of this product. This repository only provides sample code that can work as described in the official product. For detailed reviews and trading results of this product, please visit the official developer's website [here](https://forexroboteasy.com/forex-robot-review/aw-breakout-catcher-mt5-review-advanced-forex-software-for-profitable-trading/). To find the official developer of this product, please refer to the MQL5 platform.
