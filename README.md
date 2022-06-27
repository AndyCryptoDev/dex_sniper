# fast_sniper

![image](https://user-images.githubusercontent.com/103894785/175026984-afaa752b-f3b5-4ff1-b0fc-a765e42a9a3f.png)

this algorithm allows you to buy DeFi tokens (decentralized finance) on DEX (decentralized exchanges) at lightning speed at the moment of launching trading. Sniper listens to the creation of transactions adding liquidity. Methods used: AddLiquidity, Finalize, Realize. As soon as this happens, bot makes a purchase. 
You can set take profit and stop loss orders. 

## Can be used for any presale and IDO platforms, such as: DAOmaker, BSCpad, dx.app, pinksale.finance, etc.

This bot will allow you to earn very quickly right at the start of trading! But since the bot emulates hand purchase it is not afraid of anti-bot systems.

## Our bot is implemented through a telegram bot. Using the Binance Smart Chain WSS endpoint.

Its ready for BSC now and active testing: Polygon, Ethereum, Cronos networks.

Requirements:  Server Ubuntu 20.04; webhooks; python3.8 with libraries web3, pytelegrambotapi, cherrypy, pysqlite3; WSS Endpoint Binance Smart Chain; Moralis swagger API; SFTP file manager.

## We give a trial period of 72 hours free of charge 

To grow our team we rent out this bot for: a month, 3 months, half a year and all the time

Price:
- 1 month - 99 BUSD
- 3 month - 269 BUSD
- 6 month - 499 BUSD
- All the time - 700 BUSD

This price includes: 24/7 support and regular updates
- Contact: https://t.me/andycryptodev
## [DOCS](https://snpdocs.sniperbot.top)
## [Channel](https://t.me/fast_wallet_channel)

This repository contains the files required for its operation. The bot itself, we send you separately.

Let's start configuring the server to run the bot immediately.

1) Clone the repository to your server. Use this command:

```bash
git clone https://github.com/AndyCryptoDev/fast_sniper.git
```

2) From 'fast_sniper' directory you need run bash script. Use this command:

```bash
cd fast_sniper && chmod +x ./installserverbash.sh && ./installserverbash.sh
```
A couple of times during the execution of the script you will need to press "Y" to agree with the execution of the command.

We will be asked to enter some information about ourselves: two-letter country code, organization name, etc. If you don't want to write anything, put a dot in the box.

## IMPORTANT: when you get to the point to enter "Common Name", you must write the IP address of the server on which the bot will run.

<img width="769" alt="1" src="https://user-images.githubusercontent.com/103894785/163726255-60755381-a169-4076-a4dc-39e5edb47de8.png">

3) Creating a bot via https://t.me/BotFather in telegram

<img width="464" alt="2" src="https://user-images.githubusercontent.com/103894785/163727879-9b995bfa-3f88-47ad-b7c1-40748ab255f4.png">

4) Get BSC WebSocket endpoint from [QuickNode](https://www.quicknode.com/)

5) Filling out the config_snp file

```bash
nano config.py
```
![image](https://user-images.githubusercontent.com/103894785/175092858-f1999e97-06ad-41db-b050-66b9537c39fa.png)


[Video manual for Server purchase and software setup](https://www.youtube.com/watch?v=x-pgLICXQ18)


[Video manual for Setting up a server for the bot](https://www.youtube.com/watch?v=1VjPCTe6T0M)
