# Soroban Oracle

A decentralized price oracle smart contract for [Soroban](https://soroban.stellar.org/) on Stellar.

## Features

- **Multi-source Aggregation**: Combine data from multiple price feeds
- **TWAP Calculations**: Time-weighted average price support
- **Staleness Checks**: Automatic detection of outdated price data
- **Configurable Deviation**: Price change thresholds for updates
- **Authorized Reporters**: Whitelisted data provider management

## Quick Start

```bash
soroban contract build
cargo test
```

## License

MIT
