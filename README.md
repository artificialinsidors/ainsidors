

## Table Of Contents

<ul>
    <li>
		<a href="#description">Description</a>
		<ul>
			<li><a href="#features">Features</a></li>
			<li><a href="#supported-chains">Supported chains</a></li>
			<li><a href="#supported-tokens">Supported tokens</a></li>
		</ul>
	</li>
    <li>
        <a href="#getting-started">Getting started</a>
        <ul>
            <li><a href="#requirements">Requirements</a></li>
            <li><a href="#installation">Installation</a></li>
            <li><a href="#configuration">Configuration</a></li>
        </ul>
    </li>
	<li><a href="#go-premium">Go Premium</a></li>
	<li><a href="#contact">Contact</a></li>
</ul>


## Description
![Alt Text](https://i.imgur.com/8M3XqVQ.gif)

A fast and efficient bot written in NodeJS to automatically buy and sell tokens on the blockchain as soon as liquidity is added and trade is enabled.
<br><br>
The bot is extremely fast as long as you use a **good** node and not a public one. With a node from Quicknode you can expect a buy/sell transaction in less than 5 seconds.
<br><br>
The bot uploaded on github is the **lite** version of the real bot. 
You do **not** get all of the features from the premium version.

### Features

Current features supported by the **FREE** version:

- [x] Buying (BNB & ETH pairs only)
- [x] Gas estimation system
- [x] Regular liquidity sniper

Additional features supported by the **premium** version:
- [x] Buying (ALL pairs)
- [x] Multi blockchain support.
- [x] Multi-buy mode (all transactions are in the same block). 
- [x] Wrapped mode for any ETH-like token (BNB, MATIC, etc..). 
- [x] Tax checker (all pairs are supported)
- [x] Pinksale / dxsale support.
- [x] Sell using a delay
- [x] Sell using the space key
- [x] Auto / manual selling
- [x] Mempool sniping mode.
- [x] Block-offset system
- [x] Auto updates (updates are done automatically without the need of a re-download)
- [x] Trailing auto-sell.
- [x] Support

You can view the latest feature list here: https://Insnipers.io/docs/#features


### Supported chains
- Binance Smart Chain
- Avalanche
- Ethereum
- Polygon
- Cronos
- Milkomeda
- Metis
- Fantom
- Dogechain

If you wish to change the blockchain the bot will operate on, just change the WSS_NODE endpoint in config.ini to the right endpoint.

#### Public WSS Nodes
- Binance Smart Chain: wss://bsc-ws-node.nariox.org:443
- Ethereum: wss://main-light.eth.linkpool.io/ws
- Polygon: wss://rpc-mainnet.matic.network

_Note: The nodes listed above are free nodes and are NOT always online._

### Supported tokens
The bot currently supports any token using the uniswap interface.
