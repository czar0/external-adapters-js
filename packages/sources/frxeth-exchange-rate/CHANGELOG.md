# @chainlink/frxeth-exchange-rate-adapter

## 1.1.1

### Patch Changes

- [#3209](https://github.com/smartcontractkit/external-adapters-js/pull/3209) [`4724c2e`](https://github.com/smartcontractkit/external-adapters-js/commit/4724c2e421755be8fa4ad8277a0c403a6899babc) Thanks [@karen-stepanyan](https://github.com/karen-stepanyan)! - Bumped framework version

## 1.1.0

### Minor Changes

- [#3142](https://github.com/smartcontractkit/external-adapters-js/pull/3142) [`0734e093e`](https://github.com/smartcontractkit/external-adapters-js/commit/0734e093e1c10f338aaace13d552f0060576ec23) Thanks [@alecgard](https://github.com/alecgard)! - Update FraxEthDualOracle contract address and ABI.

## 1.0.5

### Patch Changes

- [#3130](https://github.com/smartcontractkit/external-adapters-js/pull/3130) [`45038be71`](https://github.com/smartcontractkit/external-adapters-js/commit/45038be71ca433291229324174c50023b2513afc) Thanks [@karen-stepanyan](https://github.com/karen-stepanyan)! - Bumped framework version

## 1.0.4

### Patch Changes

- [#3055](https://github.com/smartcontractkit/external-adapters-js/pull/3055) [`0f47b6639`](https://github.com/smartcontractkit/external-adapters-js/commit/0f47b663912413c83d266d95f7aa27089c0d1941) Thanks [@mmcallister-cll](https://github.com/mmcallister-cll)! - Bumped framework version

## 1.0.3

### Patch Changes

- [#2967](https://github.com/smartcontractkit/external-adapters-js/pull/2967) [`a7c807fc6`](https://github.com/smartcontractkit/external-adapters-js/commit/a7c807fc6ce96059c1324381ea75417872849d30) Thanks [@karen-stepanyan](https://github.com/karen-stepanyan)! - Add examples to input parameters

## 1.0.2

### Patch Changes

- [#2968](https://github.com/smartcontractkit/external-adapters-js/pull/2968) [`9fc4e5d04`](https://github.com/smartcontractkit/external-adapters-js/commit/9fc4e5d0457379600bcc763c20217dc2331cf941) Thanks [@karen-stepanyan](https://github.com/karen-stepanyan)! - Bumped framework version

## 1.0.1

### Patch Changes

- [#2959](https://github.com/smartcontractkit/external-adapters-js/pull/2959) [`e7a0196e8`](https://github.com/smartcontractkit/external-adapters-js/commit/e7a0196e8a36c012d482737820b2c89e3ace0e02) Thanks [@amit-momin](https://github.com/amit-momin)! - Bumped framework version

- [#2957](https://github.com/smartcontractkit/external-adapters-js/pull/2957) [`4f17496e9`](https://github.com/smartcontractkit/external-adapters-js/commit/4f17496e90ce4e552bd73e106b5573d812f1e14c) Thanks [@alecgard](https://github.com/alecgard)! - Bumped framework version

- [#2953](https://github.com/smartcontractkit/external-adapters-js/pull/2953) [`3c304b311`](https://github.com/smartcontractkit/external-adapters-js/commit/3c304b311ed864b4bbda580bcbeb0e28bb9298bc) Thanks [@karen-stepanyan](https://github.com/karen-stepanyan)! - Bumped framework version

## 1.0.0

### Major Changes

- 29720f068: Add frxETH-ETH Exchange Rate Adapter.

  - Adapter fetches the fraxETH-ETH exchange rate values from frxETH-ETH Dual Oracle contract.
  - Returns either priceHigh or priceLow, depending on the priceType parameter provided.
  - If `isBadData` flag is set in contract response, the EA returns an error.
