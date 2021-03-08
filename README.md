wss://stream.binance.com:9443

wss://stream.binance.com:9443/ws/btcusdt@trade

{"e":"trade","E":1615171568487,"s":"BTCUSDT","t":690249298,"p":"50636.52000000","q":"0.00172200","b":5139382731,"a":5139382729,"T":1615171568486,"m":false,"M":true}

Trade Streams
The Trade Streams push raw trade information; each trade has a unique buyer and seller.

Stream Name: <symbol>@trade

Update Speed: Real-time

Payload:

{
  "e": "trade",     // Event type
  "E": 123456789,   // Event time
  "s": "BNBBTC",    // Symbol
  "t": 12345,       // Trade ID
  "p": "0.001",     // Price
  "q": "100",       // Quantity
  "b": 88,          // Buyer order ID
  "a": 50,          // Seller order ID
  "T": 123456785,   // Trade time
  "m": true,        // Is the buyer the market maker?
  "M": true         // Ignore
}
