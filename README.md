# RMDS
Real-time Market Data Services

1. Data source is from binary stream from Hong Kong stock exchange interface.
2. The value is parsed and cached in memory with a key-value mapping.
3. The market data value is asynchronous written in a key-value table.
