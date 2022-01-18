# Yearn Keep3r CLI Jobs

This repository contains the scripts to run the following jobs of Yearn:

- Harvest-V2
- Tend-V2
- Tend-V2 (Beta)

# Yearn Harvest V2

Harvests Yearn strategies using stealth transactions.

## Config path

`node_modules/@yearn/keep3r-cli-jobs/dist/src/mainnet/harvest-v2`

## Keeper Requirements

* Must be a valid Keeper on Keep3r V1
* Have at least 50 KP3R bonded on Keep3r V1
* Should not be a contract
* Should at least have 1 ETH bonded on the Stealth Vault
* Should enable Stealth Relayer through the Stealth Vault. This should be done by calling the Vault's method `enableStealthContract`

## Useful Links

* [Job](https://etherscan.io/address/0x2150b45626199CFa5089368BDcA30cd0bfB152D6)
* [Job docs](https://github.com/yearn/keep3r-jobs/blob/master/doc/HarvestV2Keep3rStealthJob.md)
* [Stealth Relayer](https://etherscan.io/address/0x0a61c2146A7800bdC278833F21EBf56Cd660EE2a)
* [Stealth Vault](https://etherscan.io/address/0xde2fe402a285363283853bec903d134426db3ff7)
* [Stealth Relayer & Vault docs](https://github.com/yearn/keep3r-jobs/blob/master/doc/working-stealth-jobs.md)
* [Keep3r V1](https://etherscan.io/address/0x1ceb5cb57c4d4e2b2433641b95dd330a33185a44)

# Yearn Tend V2

Tends Yearn strategies.

## Config path

`node_modules/@yearn/keep3r-cli-jobs/dist/src/mainnet/tend-v2`

## Keeper Requirements

* Must be a valid Keeper on Keep3r V1
* Have at least 50 KP3R bonded on Keep3r V1
* Should not be a contract

## Useful Links

* [Job](https://etherscan.io/address/0x2ef7801c6A9d451EF20d0F513c738CC012C57bC3)
* [Job docs](https://github.com/yearn/keep3r-jobs/blob/master/doc/TendV2Keep3rJob.md)
* [Keep3r V1](https://etherscan.io/address/0x1ceb5cb57c4d4e2b2433641b95dd330a33185a44)

# Yearn Tend V2 (Beta)

Tends Yearn strategies.

## Config path

`node_modules/@yearn/keep3r-cli-jobs/dist/src/mainnet/tend-v2-2`

## Keeper Requirements

* Must be a valid Keeper on Keep3r V1
* Have at least 50 KP3R bonded on Keep3r V1
* Should not be a contract

## Useful Links

* [Job](https://etherscan.io/address/0xf72D7E44ec3F79379912B8d0f661bE954a101159)
* [Job docs](https://github.com/yearn/keep3r-jobs/blob/master/doc/TendV2Keep3rJob.md)
* [Keep3r V1](https://etherscan.io/address/0x1ceb5cb57c4d4e2b2433641b95dd330a33185a44)