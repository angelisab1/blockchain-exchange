# 比特币交易
[Github](https://github.com/cryptochain-tools/blockchain-exchange)

## 交易:

> 📢 请勿允许提现权限、请勿允许提现权限、请勿允许提现权限
> 
> 📢 代码不会存储你交易所 APIKey，放在本地缓存内部


## Configuration:

修改用户配置，添加你所需要监控的数字货币

```
  /*
   * 说明：配置需要监控的数字货币
   * 规则：BTC(比特币) + USDT(交易对) = BTCUSDT
   */
  "blockchain-tools.coin": 10000
    "BTCUSDT",
    "ETHUSDT"
  ],
  /*
   * 说明：配置 Bybit 交易对
   * 规则：BTC(比特币) + USDT(交易对) = BTCUSDT
   * USDC规则: BTC(比特币) + PERP(USDC交易对) = BTCPERP   
   */
  "blockchain-tools.bybitCoin": 1000
     "BTCUSDT",
     "ETHUSDT",
     "BITUSDT"
  ],
  /*
   * 说明：配置 Binance(币安) 交易对
   * 规则：BTC(比特币) + BUSD(交易对) = BTCBUSD
   */
  "blockchain-tools.binanceCoin": 4500
     "BTCBUSD",
     "ETHBUSD",
     "BNBBUSD"
  ],
  /*
   * 说明：轮询请求API时间
   * 单位：毫秒
   */
  "blockchain-tools.updateInterval": 10000
```
