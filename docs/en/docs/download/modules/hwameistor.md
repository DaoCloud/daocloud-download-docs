---
MTPE: windsonsea
date: 2024-01-18
hide:
  - toc
---

# Local Storage: hwameistor-operator

This page provides the offline installation package for hwameistor-operator,
which can be used to install the HwameiStor local storage module using this Operator.

## Download

| Version | Architecture | Size | Package | Checksum | Date |
| ------- | ------------ | --------- | ------- | ------------- | ----------- |
| [v0.13.1](../../storage/hwameistor/release-notes.md#v0131) | AMD 64 | 1.62 GB | [:arrow_down: hwameistor-operator_v0.13.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hwameistor-operator_v0.13.1_amd64.tar) | [:arrow_down: hwameistor-operator_v0.13.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hwameistor-operator_v0.13.1_amd64_checksum.sha512sum) | 2023-11-06 |

## Verification

In the directory where you downloaded the offline installation package and checksum file,
replace `v0.13.1_amd64` with the actual version, and run the following command to verify the integrity:

```sh
echo "$(cat hwameistor-operator_v0.13.1_amd64_checksum.sha512sum)" | sha512sum -c
```

If the verification is successful, the output will be similar to:

```none
hwameistor-operator_v0.13.1_amd64.tar: ok
```

## Installation

Refer to [hwameistor-operator installation procedure](../../storage/hwameistor/install/deploy-operator.md) for installation.
If you have any license key-related questions, please contact the DaoCloud delivery team.
Email info@daocloud.io or call 400 002 6898.
