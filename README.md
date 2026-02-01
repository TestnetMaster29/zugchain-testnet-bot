ZugChain Bot (Ethers.js)

Automated bot for interacting with ZugChain Testnet using ethers.js v6.
Supports multi-wallet balance check and is ready to be extended for staking, claiming, and automation.

Requirements

-Node.js v18 or higher (Node v22 recommended)
-npm
-ZugChain private keys


Installation



clone

```
git clone https://github.com/TestnetMaster29/zugchain-testnet-bot.git
cd zugchain-testnet-bot
```


Install dependencies

```
npm install
```


Add your wallets

Edit accounts.txt
(one private key per line, without quotes)

```
nano accounts.txt
```

0xPRIVATEKEY1

0xPRIVATEKEY2



Run the Bot

```
node index.js
```



Interactive Options

When running, the bot will ask:
Auto claim faucet? (y/n)
Stake amount (ZUG)
Auto claim stake? (y/n)

(Current version initializes wallets and checks balances.
Staking & claiming logic can be added next.)



Security Warning

❗ Never share your private keys

❗ Do not commit accounts.txt to GitHub

Use testnet wallets only
