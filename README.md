# PLAZA FINANCE BOT
Plaza is a platform for on-chain bonds and leverage on Base.

Plaza is a platform for programmable derivatives built as a set of Solidity smart contracts on Base. It offers two core products: bondETH and levETH, which are programmable derivatives of a pool of ETH liquid staking derivatives (LSTs) and liquid restaking derivatives (LRTs) such as wstETH. Users can deposit an underlying pool asset like wstETH and receive levETH or bondETH in return, which are represented as ERC20 tokens. These tokens are composable with protocols such as DEXes, lending markets, restaking platforms, etc.

[Click This to Register Plaza Finance](https://testnet.plaza.finance/rewards/wkT6SilPvFL5)

[Get your Base Sepolia Testnet](https://docs.base.org/docs/tools/network-faucets/)

[Bridge your ETH Sepolia > Base Sepolia](https://sepolia-bridge.base.org/deposit)

## Features

- **Auto Daily Transaction**
- **Auto Get Faucets**
- **Auto Generate New Wallets**
- **Send Fund To Existing Address**
- **All Wallets information Saved In wallets.json** 


## Requirements

- **Node.js**: Ensure you have Node.js installed.
- **npm**: Ensure you have npm installed.
- **Wallets must have $1 in eth/base/arb mainnet to get faucet**
- **Use feature auto send to send fund to existing wallet:** send `0.0003` eth for each addr

## Buy Proxies
- Free Proxies Static Residental: 
   - [WebShare](https://www.webshare.io/?referral_code=p7k7whpdu2jg)
   - [ProxyScrape](https://proxyscrape.com/?ref=odk1mmj)
   - [MonoSans](https://github.com/monosans/proxy-list)
- Paid Premium Static Residental:
   - [922proxy](https://www.922proxy.com/register?inviter_code=d03d4fed)
   - [Proxy-Cheap](https://app.proxy-cheap.com/r/JysUiH)
   - [Infatica](https://dashboard.infatica.io/aff.php?aff=544)

## Setup

1. Run This quick installation script
   ```bash
   source <(curl -s https://raw.githubusercontent.com/ryzwan29/plaza-finance/main/quick-installation.sh)
   ```
2. Insert your own wallet (single wallet):
   - Create file with name ``wallets.json`` with format:
     
     ```bash
     [
       {
       "address": "0xyouraddress",
       "privateKey": "0xyourrivatekey",
       "mnemonic": "your mnemonic phrase key"
       },
       {
       "address": "0xyouraddress-2",
       "privateKey": "0xyourrivatekey-2",
       "mnemonic": "your mnemonic phrase key-2"
       }
     ]
     ```
3. Run script
   ```bash
   npm run start
   ```

4. Additional Feature (multi wallets):

      - create new wallets
         ```bash
         npm run create
         ```

      - send fund to existing address
          ```bash
          npm run autosend
          ```

      - distribute eth base sepolia to all wallets in `wallets.json`
         ```bash
         npm run faucet
         ```
          
      - use proxy: its optional, paste proxy in the proxy.txt file. 1 proxy per line.
          ```bash
          nano proxy.txt
          ```
         format : `http://user:password@ip:port`


## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the [MIT License](LICENSE).
