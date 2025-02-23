# CHANGELOG

## 2.0.5 - 2022-05-23

- Fix method convertCurrenciesV2 by adding header `X-Idempotence-Uuid` to request

## 2.0.4 - 2019-03-12

- Upgrade dependency minimist package from v1.2.5 to v1.2.6

## 2.0.3 - 2022-02-22

- Rename github repository from `transferwise-client` to `wise-client`
- Rename `TransferWise` to `Wise` in README.md file
- Rename `TransferWise` to `Wise` in package.json file

## 2.0.2 - 2022-02-21

- Correct README.md Usage part.

## 2.0.1 - 2022-02-21

- Change the name of the package back to `transferwise` since `wise` is not available.

## 2.0.0 - 2022-02-21

- Total rework of the transferwise client
  - Add CHANGELOG.md file.
  - Add tests using jest.
  - Change the name of the package in consequence of the name of the service from `transferwise` to `wise`.
  - Add support for [strong-customer-authentication](https://api-docs.transferwise.com/#strong-customer-authentication) using option scaPrivateKey.
  - Upgrade API endpoints calls to use its newer versions.
  - Upgrade to node LTS version 16.
