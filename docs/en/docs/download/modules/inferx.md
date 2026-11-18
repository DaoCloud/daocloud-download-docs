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
| [v0.6.1](../../inferx/intro/release-notes.md) | AMD 64 | 21.49 GB | [:arrow_down: inferx_v0.6.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.6.1_amd64.tar) | [:arrow_down: inferx_v0.6.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.6.1_amd64_checksum.sha512sum) | 2026-10-29 |
| [v0.6.0](../../inferx/intro/release-notes.md) | AMD 64 | 21.48 GB | [:arrow_down: inferx_v0.6.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.6.0_amd64.tar) | [:arrow_down: inferx_v0.6.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.6.0_amd64_checksum.sha512sum) | 2026-10-19 |
| [v0.5.0](../../inferx/intro/release-notes.md) | AMD 64 | 22.27 GB | [:arrow_down: inferx_v0.5.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.5.0_amd64.tar) | [:arrow_down: inferx_v0.5.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.5.0_amd64_checksum.sha512sum) | 2026-09-03 |
| [v0.4.0](../../inferx/intro/release-notes.md) | AMD 64 | 9.90 GB | [:arrow_down: inferx_v0.4.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.4.0_amd64.tar) | [:arrow_down: inferx_v0.4.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.4.0_amd64_checksum.sha512sum) | 2026-07-20 |
| [v0.3.0](../../inferx/intro/release-notes.md) | AMD 64 | 10.77 GB | [:arrow_down: inferx_v0.3.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.3.0_amd64.tar) | [:arrow_down: inferx_v0.3.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.3.0_amd64_checksum.sha512sum) | 2026-06-08 |
| [v0.2.0](../../inferx/intro/release-notes.md) | AMD 64 | 10.77 GB | [:arrow_down: inferx_v0.2.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.2.0_amd64.tar) | [:arrow_down: inferx_v0.2.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.2.0_amd64_checksum.sha512sum) | 2026-05-12 |
| [v0.1.0](../../inferx/intro/release-notes.md) | AMD 64 | 9.98 GB | [:arrow_down: inferx_v0.1.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.1.0_amd64.tar) | [:arrow_down: inferx_v0.1.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.1.0_amd64_checksum.sha512sum) | 2026-04-27 |

## Verification

In the directory where the offline installation package and checksum file are downloaded (using `v0.2.0_amd64` as an example), run the following command to verify integrity:

```sh
echo "$(cat inferx_v0.2.0_amd64_checksum.sha512sum)" | sha512sum -c
```

If the verification succeeds, the output will look like:

```none
inferx_v0.2.0_amd64.tar: ok
```

## Installation

Refer to the offline installation steps for the inference accelerator.
If you have any license key-related questions, please contact the DaoCloud delivery team.
Email info@daocloud.io or call 400 002 6898.
