# PlasmaFi PlasmaSwap-Subgraph

Dex basis on Automated Market Make protocol (AMM) - Uses a mathematical formula to determine the price of an asset. Assets are priced according to a pricing algorithm, unlike traditional exchanges that use an order book.

This subgraph dynamically tracks any pair created by the PlasmaSwap factory. It tracks of the current state of PlasmaSwap contracts, and contains derived stats for things like historical data and USD prices.

- Aggregated data across pairs and tokens,
- Data on individual pairs and tokens,
- Data on transactions
- Data on liquidity providers
- Historical data on PlasmaSwap, pairs or tokens, aggregated by day

### ROUTER ADDRESS 

PlasmaSwap
```
[ChainId.MAINNET]: '0x5ec243F1F7ECFC137e98365C30c9A28691d86132'
```

### FACTORY ADDRESS 

PlasmaSwap
```
[ChainId.MAINNET]: '0xd87Ad19db2c4cCbf897106dE034D52e3DD90ea60'
```

### INIT CODE HASH

PlasmaSwap
```
[ChainId.MAINNET]: '611ee9501fb19c9df82695e66f6c58d69d86907b531dfbed652231515ae84081',
```

In-depth documentation on PlasmaDEX is available at [docs.plasma.finance](https://docs.plasma.finance)