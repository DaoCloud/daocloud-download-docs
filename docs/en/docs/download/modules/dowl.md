---
MTPE: windsonsea
date: 2026-09-30
hide:
  - toc
---

# Security Management

This page provides offline packages for different versions of the Dowl security management module.

## Download

| Version | Architecture | Size | Package | Checksum | Date |
| ------- | ------------ | --------- | ------- | ------------- | ------------ |
| [v0.7.0](../../kpanda/intro/release-notes.md) | AMD 64 | 167.29 MB | [:arrow_down: dowl_v0.7.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dowl_v0.7.0_amd64.tar) | [:arrow_down: dowl_v0.7.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dowl_v0.7.0_amd64_checksum.sha512sum) | 2023-11-26 |
| [v0.6.0](../../kpanda/intro/release-notes.md) | AMD 64 | 167.29 MB | [:arrow_down: dowl_v0.6.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dowl_v0.6.0_amd64.tar) | [:arrow_down: dowl_v0.6.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dowl_v0.6.0_amd64_checksum.sha512sum) | 2023-11-02 |
| [v0.5.1](../../kpanda/intro/release-notes.md) | AMD 64 | 167.29 MB | [:arrow_down: dowl_v0.5.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dowl_v0.5.1_amd64.tar) | [:arrow_down: dowl_v0.5.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dowl_v0.5.1_amd64_checksum.sha512sum) | 2023-09-12 |
| [v0.4.0](../../kpanda/intro/release-notes.md) | AMD 64 | 163 MB | [:arrow_down: dowl_v0.4.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dowl_v0.4.0_amd64.tar) | [:arrow_down: dowl_v0.4.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dowl_v0.4.0_amd64_checksum.sha512sum) | 2023-8-25 |

## Verification

To verify the integrity of the downloaded offline packages and checksum files,
take v0.4.0 as an example and run the following command in the directory:

```sh
echo "$(cat dowl_v0.4.0_amd64_checksum.sha512sum)" | sha512sum -c
```

Upon successful verification, the result will be similar to:

```none
dowl_v0.4.0_amd64.tar: ok
```

## Installation

Refer to [offline upgrade of the security management module](../../kpanda/user-guide/security/offline-upgrade-dowl.md) for installation.
If you have any license key-related questions, please contact the DaoCloud delivery team.
Email info@daocloud.io or call 400 002 6898.
