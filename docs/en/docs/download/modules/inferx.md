---
MTPE: windsonsea
date: 2026-05-12
hide:
  - toc
---

# Inference Acceleration

This page provides offline installation packages for different versions of the inference acceleration module.

## Download

| Version | Architecture | File Size | Package | Checksum File | Release Date |
| ---- | --- | ------ | ------ | ------ | ------- |
| [v0.2.0](../../inferx/intro/release-notes.md) | AMD64 | 10.77 GB | [:arrow_down: inferx_v0.2.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.2.0_amd64.tar) | [:arrow_down: inferx_v0.2.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.2.0_amd64_checksum.sha512sum) | 2026-05-12 |
| [v0.1.0](../../inferx/intro/release-notes.md) | AMD64 | 9.98 GB | [:arrow_down: inferx_v0.1.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.1.0_amd64.tar) | [:arrow_down: inferx_v0.1.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.1.0_amd64_checksum.sha512sum) | 2026-04-27 |

## Verification

In the directory where the offline installation package and checksum file are downloaded (using `v0.1.0_amd64` as an example), run the following command to verify integrity:

```sh
echo "$(cat inferx_v0.1.0_amd64_checksum.sha512sum)" | sha512sum -c
```

If the verification succeeds, the output will look like:

```none
inferx_v0.1.0_amd64.tar: ok
```

## Installation

For first-time installation, please [apply for a free trial](../../dce/license0.md) or contact us for licensing: email [info@daocloud.io](mailto:info@daocloud.io) or call 400 002 6898.
If you have any license key-related issues, please contact the DaoCloud delivery team.
