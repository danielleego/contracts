# contracts

zy: 0x95d8976d18CD6Ee19Bd5Bcd7C46B444B9219E78c


https://api.thegraph.com/subgraphs/name/danielleego/aegis-arbitrum-goerli


query MyQuery {
  pairs {
    reserveUSD // tvl
    token0 {
      symbol
      id
    }
    token1 {
      id
      symbol
    }
    id
  }
}
