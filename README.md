# mvcpool-manual

Welcome to MvcPool.com

MvcPool is an MVC-specialized mining pool supported by the founding members of MVCLabs. It exclusively mines MVC and is fully optimized to meet the increasing transaction processing demands of the MVC network.

## Pool Attributes

**Algorithm** : SHA256, Same like BTC,BCH,BSV etc.

**Payout Method** : PPLNS(Pay per last N shares)

**N calculation** : N = (blockDiff * 5) / shareDiff

**Share diff** : 2000000

**Mature Requirement** : 100 Confirmations

**Fee Rate** : 2% Block rewards

**AsicBoost** : Supported

**Mining url** : mine.mvcpool.com:6666 (please register first)


## Steps

### Register pool account

Testnet:
https://console-testnet.mvcpool.com/

Mainnet:
https://console.mvcpool.com/

Register and login your account first, keep your password safe.

### See your Connection Dashboard

![img.png](img.png)

### Connect To The Pool

Use the connection URL, the stratum username, and password to connect to the pool. If successfully connected, you should see your hashrate displayed within 5 minutes.

## FAQ

### Mining Related

#### What is PPLNS

https://medium.com/luxor/mining-pool-payment-methods-pps-vs-pplns-ac699f44149f

Pay Per Last N Share (PPLNS) is another popular payment method. It offers payment to miners as a percentage of shares they contribute to the total shares (N).

#### Why I cannot see my hashrate

Your hash rate is calculated based on how many shares you submitted in the past five minutes. If your hash rate is too low to find a share in 5 minutes, you may not see your hashrate.
If your hashrate is enough, please confirm your rejection rate. Normally, valid shares do not get rejected. If it keeps getting rejected, please stop using and contact the team.

#### Why MvcPool hash is higher than NetworkHash

The pool hash and user hash are calculated in real-time (5-minute window), while the networkHash is an average of the last day. Burst pool hash can surpass network hash.
Real-time network hash cannot be calculated; it can only be estimated by a moving average of the last blocks.

#### Why my payout takes 100 confirmation to mature

Your payout comes from the real-founded block coinbase reward. Coinbase reward takes 100 confirmations to be spendable, a common feature in Bitcoin-like blockchains (same logic as BTC, BCH, BSV). After reaching 100 confirmations, your payout will be sent to your pool wallet instantly, and you can withdraw it.

#### Do you support Asicboost

Yes, we support AsicBoost and recommend miners to activate it. It can increase ROI by around 20%.

### Wallet Related

#### Why your pool have a wallet integrated

Due to the nature of PPLNS, it's easier to manage and distribute rewards by user account. This wallet address will not change; it's bound to your account.

#### What if I lost my password

Contact the team using your registered email address to recover.


#### Can I use MVCPool wallet address to receive private mining coinbase reward

No, we suggest not doing so. The wallet is not designed to receive coinbase from private mining. If you do that, your wallet will be unspendable until your private coinbase gets 100 confirmations.

### Team and Contact

#### Who maintains this pool

The MVC infrastructure team maintains the pool, handling daily operations, pool development, and customer support.

#### Where is the team

The team is mainly located in Tokyo, Japan, with some members working globally.

#### How does the pool profit

We take mining fees to maintain the pool, covering costs like development, cloud computing, and operations. We've also initiated a draft to lower the fee to zero to benefit all MVC miners. The cost will be covered by MVC treasury as infrastructure investment. The draft will be openly discussed and voted on after DAO establishment.

#### How to Contact the team

Join our Discord: https://discord.gg/3tavfAKg. 
Find the MvcPool channel and raise your questions. Your request will be responded to as soon as possible.
