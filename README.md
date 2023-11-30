# RSI Divergence Scanner MT4

This code is a custom indicator for MetaTrader 4 (MT4) that scans multiple symbols and timeframes for RSI (Relative Strength Index) divergences. It identifies both regular and hidden divergences, which can be used as potential signals for trend reversals in forex trading.

## Developer Information

- Developer: Forex Robot Easy Team
- Developer's site: [forexroboteasy.com](https://forexroboteasy.com)

## Product Description

The RSI Divergence Scanner MT4 is a powerful tool for forex traders who use RSI as a technical indicator for trend analysis. It scans multiple symbols and timeframes to identify potential trend reversals based on RSI divergences.

- Regular Divergence: When price makes a higher high but RSI makes a lower high or vice versa.
- Hidden Divergence: When price makes a lower low but RSI makes a higher low or vice versa.

The indicator calculates the divergence value between the current and previous price and RSI, and compares it to a specified threshold. If the divergence value exceeds the threshold, a divergence is detected and a log message is generated.

The code allows customization of the symbols and timeframes to scan, as well as the divergence threshold value. It also includes logging functionality to track and record the detected divergences.

**Note:** This code is provided as a sample and is not the official product developed by Forex Robot Easy. It demonstrates the functionality described in the [RSI Divergence Scanner MT4 review](https://forexroboteasy.com/forex-robot-review/rsi-divergence-scanner-mt4-review-of-trend-reversal-tool/). To find the official developer and obtain the official product, please refer to the MQL5 website.

## Features

- Scans multiple symbols and timeframes for RSI divergences
- Detects both regular and hidden divergences
- Customizable symbols, timeframes, and divergence threshold
- Logging functionality to track and record detected divergences

## Usage

1. Install the RSI Divergence Scanner MT4 indicator in the MetaTrader 4 platform.
2. Set the desired symbols to scan by modifying the `symbols` array variable.
3. Set the desired timeframes to scan by modifying the `timeframes` array variable.
4. Adjust the divergence threshold value by modifying the `divergenceThreshold` variable.
5. Enable or disable logging by modifying the `enableLogging` variable.
6. Run the indicator and monitor the generated log messages for detected divergences.
7. Implement your trading logic based on the detected divergences.

## Limitations

- This code is intended as a sample and may require further customization to fit specific trading strategies.
- The effectiveness of RSI divergences as trading signals may vary depending on market conditions and other factors.
- Additional risk management and confirmation strategies are recommended when using RSI divergences as trading signals.

For detailed reviews and trading results of the official RSI Divergence Scanner MT4 product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/rsi-divergence-scanner-mt4-review-of-trend-reversal-tool/).
