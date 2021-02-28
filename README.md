# valid8r

An open-source command line interface for linting your Ethereum 2.0 validator set up, maintained by Pondron LLC.

## Overview

valid8r is a tool to ensure Ethereum 2.0 validator set-up integrity to give peace of mind to the implementer and more importantly ensure the network runs smoothly. valid8r will acts as a linting tool and reads out to the implementer what system settings are correct, what systems settings need to be changed, and what system settings do not follow best practices.

## Updates to `master` branch

Main development of new features should be directed towards the upstream
git repos. The `master` branch of this repo will periodically pull in new
changes from upstream to provide a point for integration.

## `valid8r` usage

```
--config 
```

## Ethereum Client Support

| Client         | Version |
| -------------- | ------- |
| geth           |         |
| besu           |         |
| nethermind     |         |
| openethereum   |         |
| lighthouse     |         |
| prysm          |         |
| teku           |         |
| nimbus         |         |

## OS Support

- macOS
- Ubuntu LTS

## Tests

Unit tests will be included where applicable and can be run from the directory with

```
cargo test
```

## Contributing

If you are looking to contribute, please head to the
[Contributing](https://github.com/pondron/valid8r/blob/master/CONTRIBUTING.md) section.