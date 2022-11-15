# mvcpool-manual
How to use mvcpool to mine mvc coins

## Testnet

### Register pool account
https://console-testnet.mvcpool.com/

Register and login your account first, keep your password safe.

### Download cpuminer (ignore for asic)
Download CPU miner(ignore this if you already have asic miner)
https://github.com/pooler/cpuminer/releases/tag/v2.5.1

Go to this page , you can see your stratum url and username.
https://console-testnet.mvcpool.com/#/connect

### Run CPU miner(or asic)

replace the following stratum url and userName, password is same as userName.

you can also change threads count according to your cpu cores.

```
./minerd -o stratum+tcp://mine.metasv.com:8654 -a sha256d -O userName:userName -D -P --threads=4
```

Asic miner is also the same, configure your stratum url and userName, then start mining
