# GUI Pancakeswap 2 and Uniswap 3 SNIPER BOT V2 🏆🥇 
<H3>(MOST ADVANCE TRADING BOT SUPPORT WINDOWS LINUX MAC)</H3>

## FINALLY PANUNISWAP VERSION 2 REALEASED :
#### 4X Faster with cython
#### Fix bug BUY token After add LIQUIDITY
#### Fix bug on android 11 (bug:close after start)
#### Now you can set SLIPPAGE 0.1 
#### ADD Auto SLIPPAGE

 
<H2>(AUTO BUY TOKEN ON LAUNCH AFTER ADD LIQUIDITY)</H2>
<H5>Sniper bot that watches when taxes/anti buy are removed from a contract, then quick snipes, with honeypot detector, and also keybinding for fair launches</H5>
<H5>UPDATE: MUTI TRADE TOKEN ENABLE TRADE 10 TOKEN IN SAME TIME </H5>

A Pancakeswap and Uniswap trading client (and bot) with market orders, limit orders, stop-loss, custom gas strategies, a GUI and much more.

<a href="https://ibb.co/6Hs7WPt"><img src="https://i.ibb.co/QPm3KNH/pan-UNIswap-bot.jpg" alt="pan-UNIswap-bot" border="0"></a>

[![Version](https://img.shields.io/badge/Codename-BlackHat-red.svg?maxAge=259200)]()
[![Stage](https://img.shields.io/badge/Release-Stable-brightgreen.svg)]()
[![Build](https://img.shields.io/badge/Supported_OS-WINDOWS-orange.svg)]()
[![Available](https://img.shields.io/badge/Available-LINUX-orange.svg?maxAge=259200)]()
[![Documentation](https://img.shields.io/badge/PANUNISWAP-BOT-red.svg?maxAge=259200)]()
[![Contributions Welcome](https://img.shields.io/badge/Type-FREE-blue.svg?style=flat)]()
 
<H4> FOR PREMIUM VERSION AND MORE INFORMATION EMAIL ME </H4>

<H3>WHAT IS UNIQUE PANUNISWAP-BOT</h3>🤠

- Support Windows 10 ,Linux and Mac OS
- Add uniswap V3 & pancakeswap v2 Fantom Matic Solona KuCoin Chain OKEXchain 
- Added multiple DEXs
- Added BNB ETH BUSD DAI USDC USDT WBTC as maincoin option
- Force Buy and Force Sell buttons, when clicked it will buy or sell with your chosen settings (excluding limit price)
- set manual SLIPPAGE 
- set stop-less price
- Speed adjustable
- The program now determines the name and decimals of the token automatically

 
  

<H2>HOW TO USE</H2>🏆

1. An ethereum/bsc address.
2. Open "configfile.py" (with notepad) on line 3 and 4 add wallet address and phrase or private key.
3. Run python3 panUNIswap_bot.py

(Also you can use phrase key just use space between words)

<H2>How Find Private Key</H2>
https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key

### Install

First of all, you need install Python3+
Run on Android you need Install [Termux](https://termux.com/)  

### Install Requirements:  
#### python3
#### pip install -r requirements.txt
#### python3 panUNIswap_bot.py


<H4>ALSO YOU CAN COMPILE PANUNISWAP-BOT TO EXE WITH PYINSTALLER</H4>



# Screenshot📺

<a href="https://ibb.co/CJmgG9M"><img src="https://i.ibb.co/8zNqZxd/2.png" alt="2" border="0"></a>




<H2>Functions</H2>🧳

<b>Main coin/token</b>: The token or coin you want to trade tokens for and with

<b>Token address</b>: Fill the token address of the token you want to trade (such as 0x0000000000000000000000000000000000000000)

<b>Notes</b>: A place to fill in notes, such as the name of the token
 
<b>Sell($)</b>: The price you want the trader to sell the token for (0.01 = 1 dollar cent)

<b>Buy($)</b>: The price you want the trader to buy the token for (0.01 = 1 dollar cent)

<b>Trade w/ main</b>: Toggle if you want to activate trading with your main-coin/token

<b>Trade w/ token (Experimental!)</b>: Toggle if you want to trade the token with other BEP20 tokens of which this option is activated (see tokentokennumerator)

<b>Stoploss</b>: Toggle to activate stoploss (0.01 = 1 dollar cent)

<b>Second(s) between checking price</b>: Standard is 4 seconds. With a infura server with max 100.000tx/day 4 seconds is good for 2 activated token 24hr/day

<b>Seconds waiting between trades</b>: depends on how fast transactions finalize

<b>Max slippage</b>: The maximum slippage you want to allow while trading (3 = 3%)
 
<b>$ to keep in ETH/BNB after trade</b>: The amount of ETH/BNB you want to keep after each trade (excluding transaction fees) in terms of $.

<b>GWEI</b>: The amount of gas you want to use for each trade (5 GWEI is fine for PCS). When trading on uniswap, This becomes the max GWEI you want to pay on the eth network, the GWEI will be determined from ethgasstation.com

<b>Different deposit address</b>: Use this if you want the swap output to go to a different address (without extra fees)

<b>Tokentokennumerator (Experimental!)</b>: This value lets you trade ERC tokens with each other. The code to create the value is as followed:
<pre>if pricetoken1usd > ((token1high + token1low) / 2) and pricetoken2usd < ((token2high + token2low) / 2):
  token1totoken2 = ((pricetoken1usd - token1low) / (token1high - token1low)) / ((pricetoken2usd - token2low) / (token2high - token2low))</pre>
  
If you dont want to wait till the token1 is sold for the maincoinoption, because you are uncertain whether token2 will still be at this price level or think that token1 will     drop, you can use this function. To use this function, "Trade with ERC" should be activated for at least 2 tokens, and the highs and lows should be set seriously.
    
  As an example, if the current price of token1 is $0.9 and its set "high"=$1 and "low"=$0, the value of this token is seen as "90%". Token2 also has a high of $1, but the         current price is 0.2$, value of this token is seen as 20%. The tokentokenmnumerator is set at 3.3. If we divide the 90% by the 20%, we get 4.5, which is higher than 3.3, which   means that token1 gets traded for token2 instantly. If the tokentokennumerator was set to 5, the swap would not happen.
  



 
## Youtube Videos 🎥

# WATCH VIDEO == https://youtu.be/zFm15cuYD-c

 
<a href="https://ibb.co/rZ5jwTz"><img src="https://i.ibb.co/BgTpCdQ/Skq-YCo-Pa-RGm4-Iv-JEm-WF5-Pancake-Swap-vs-Uniswap.png" alt="Skq-YCo-Pa-RGm4-Iv-JEm-WF5-Pancake-Swap-vs-Uniswap" border="0"></a><br /><a target='_blank' href='https://nl.imgbb.com/'></a><br />


<H2>Disclosure</H2>
I own some of the tokens portayed in the gif. These tokens are used only for example purposes and are not meant to be an endorsement. I am not affiliated with these tokens or any subsidiaries.

  
