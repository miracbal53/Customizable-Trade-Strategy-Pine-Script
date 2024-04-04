# Customizable-Trade-Strategy-Pine-Script

![Ekran görüntüsü 2024-04-04 045321](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/f16ebc84-f5a0-4f5c-a621-b70ac56a25e1) 

![Ekran görüntüsü 2024-04-04 045339](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/4c9ad0c6-72ac-477c-90fc-2517e11f79fa)

FOR VOLUME CONFİRM ? 
The strategy requires you to choose one of two volume confirmation indicators.

1. Waddah Atar Exploison

The Waddah Attar Explosion indicator provides valuable signals that can guide traders in their decision-making process.

1-Volatility-Based Entries: When the WAE line crosses above the signal line, it generates a bullish signal, suggesting a potential long entry. Conversely, when the WAE line crosses below the signal line, it generates a bearish signal, indicating a potential short entry.
2-Volatility Breakouts: When the WAE line spikes above a certain threshold, it signifies a volatility breakout to the upside, signaling potential long opportunities. Conversely, when the WAE line plunges below the threshold, it indicates a volatility breakout to the downside, suggesting potential short opportunities.
3-Trend Confirmation: When the WAE line remains consistently above the signal line, it indicates a strong bullish trend. Conversely, when the WAE line stays consistently below the signal line, it suggests a strong bearish trend.

![Ekran görüntüsü 2024-04-04 050729](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/2d3b4371-bea2-445e-a2c1-dbec48dc4c44)

Long Condition = A green bar closing above the Explosion Line and within the Dead Zone.
Short Condition = A red bar closing above the Exploison Line and within the Dead Zone.

2. KUSKUS Startlight + EMA 

The KusKus Starlight indicator is an oscillator built using Fisher price transformation. It is also normalized over the last range periods. Smoothing can be adjusted in the parameters.

![Ekran görüntüsü 2024-04-04 045618](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/72b6d562-987d-4cf7-a989-3757e9a0959c)

A green bar indicates an upward trend, while a red bar indicates a downward trend, with the yellow line representing the average.

Long Condition = Green bar closing above the ema 
Short Condition = Red bar closing under the ema

TREND INDICATOR ?

1. THREE TILSON T3 

The Tillson T3 indicator, also known as T3 or Tillson moving averages, was developed to improve the lag and false signals often found in moving averages. T3 produces smoother and more responsive results compared to other average area trend indicators such as SMA, EMA, etc. Trend reversals can be felt using T3.

We offer you Tillson T3, which allows you to adjust three different lengths and is suitable for opening and closing.

You should enter the values in accordance with the sequence of long, medium, and short. For it to function correctly, the long T3 should not be 200 while the short T3 is 300.

 !! At least two T3s must be open. !!

Long Condition = The short T3 should be above the medium T3, and the medium T3 should be above the long T3, with the price above the T3.
Short Condition = The short T3 should be under the medium T3 and the medium T3 should be under the long T3, with the price under the T3.


![Ekran görüntüsü 2024-04-04 045538](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/2b943048-be01-4fbc-8195-42aa39d6edd3)

TREND POWER CONFIRMATION ?

1. ADX 

ADX is an indicator that determines the strength of a trend. The larger the ADX value, the stronger the trend. ADX only indicates whether the market is trending or not, it does not provide information about the direction of the trend. When ADX starts to rise from low levels, it signifies the emergence of a new trend. Conversely, when it starts to decline from high levels, it can be interpreted as the market entering a consolidation period for a while.


![Ekran görüntüsü 2024-04-04 050755](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/c64fa821-53fb-407d-8298-34af3ed2a296)


Long Condition = ADX > 25
Short Condition = ADX > 25

2. GCV (Garman Klass Volatility)

Garman Klass is a volatility estimator that incorporates open, low, high, and close prices of a security.

Garman-Klass volatility extends Parkinson's volatility by taking into account the opening and closing price. As markets are most active during the opening and closing of a trading session, it makes volatility estimation more accurate.

We added an average to the GCV.

![Ekran görüntüsü 2024-04-04 050631](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/409fd156-0a96-4fd8-a13d-072445ba7881)

Red Line = GCV 
White Line = GCV AVG

Long Condition = Red Line > White Line
Short Condition = Red Line > White Line

3. NO

You may choose not to use the trend confirmation indicator if you prefer.

HOW Take Profit and Stop Loss ?

Our first take profit and stop-loss points are provided by ATR.

You can set your stop based on how many ATRs away you want it to be, and also define how many R:R you want to achieve with your reward.

2. TP 

If you are going to use two take profits, we recommend closing half of the position at the first take profit and the other half at the second take profit.

The second method for taking profit is as follows: if you choose T3, you expect the candle's closing to be below the active shortest T3 line; if you choose SuperTrend, you expect SuperTrend 1 to be downwards.

![Ekran görüntüsü 2024-04-04 051017](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/d45e2198-aae9-444e-84ee-b5642ee23b1b)

![Ekran görüntüsü 2024-04-04 045943](https://github.com/miracbal53/Customizable-Trade-Strategy-Pine-Script/assets/108282437/c45f3c06-f64e-43fd-af45-00cc03e0b0d5)
