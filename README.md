# AlgoTrdingMT4
This is a working demo expert advisor not intended to be used for real money forex trading.

CustomFunctions1.mqh file has important utility functions that can be used to avoid infinite loops and catch errors.

To run the expert advisor:
1) Download files in their respective folders within MetaQuotes -> Terminal -> TerminalNumber -> MQL4.
2) Open Terminal
3) Open Strategy tester (View -> Strategy Tester / Ctrl + R)
4) Select "Expert Advisor" and choose "BBStrat"
5) Symbol: GBP/USD, Period: H4, Model: Every Tick, Spread: Current
6) Click Start

Make sure you download enough tick data before running the backtest.
Tools -> History Center -> Choose your favorite pair and download data.
