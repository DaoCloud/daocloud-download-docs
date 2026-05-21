---
MTPE: windsonsea
date: 2026-05-15
hide:
  - navigation
---

# DCE 5.0 Enterprise with Installer v0.40.0

This page provides offline installation packages and checksum files for DCE 5.0 Enterprise edition.

[Return to Download Index](../index.md#download-dce-50-enterprise){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| -------- | ------- | ------------ | ---- | -------- | ---- |
| offline-v0.40.0-amd64.tar | v0.40.0 | AMD64 | 35.06 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.40.0-amd64.tar) | 2026-05-15 |
| offline-v0.40.0-arm64.tar | v0.40.0 | <font color="green">ARM64</font> | 31.66 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.40.0-arm64.tar) | 2026-05-15 |

## Verification

Go to the directory where the offline package is downloaded.

=== "AMD64"

    Run the following command to verify:

    ```sh
    echo "ce970ee13c534fdebdbaa610087f026d865586a4641bef36cf391321b1d0542ffda89b6b88424d33edc9bc84a712e3d05abf9eabe5ea9309c31236a82cecdc91  offline-v0.40.0-amd64.tar" | sha512sum -c
    ```

    If successful:

    ```none
    offline-v0.40.0-amd64.tar: OK
    ```

=== "<font color="green">ARM64</font>"

    Run the following command to verify:

    ```sh
    echo "d9c44b69c25bc5e26f4b722bfb6c1d274c7f707edb31af6fbd2e2427c51299a4c6379daa847bf551927117fca15ab0ed4dde14bea81845272bd09476fa087227  offline-v0.40.0-arm64.tar" | sha512sum -c
    ```

    If successful:

    ```none
    offline-v0.40.0-arm64.tar: OK
    ```

## Installation

After verification, extract:

=== "AMD64"

    ```sh
    tar -xvf offline-v0.40.0-amd64.tar
    ```

=== "<font color="green">ARM64</font>"

    ```sh
    tar -xvf offline-v0.40.0-arm64.tar
    ```

- See [Enterprise Installation Guide](../../install/commercial/start-install.md)
- Contact: info@daocloud.io or 400 002 6898

## Modules

DCE 5.0 Enterprise includes modules such as Global Management, Container Management, Observability, LLM Studio, AI Lab, Workbench, Multi-Cloud Orchestration, Microservice Engine, Service Mesh, and more.

## More

- [Online Docs](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
