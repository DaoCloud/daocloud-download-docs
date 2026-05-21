---
MTPE: windsonsea
date: 2026-05-15
hide:
  - navigation
---

# DCE 5.0 Community v0.40.0

This page provides offline installation packages for DCE 5.0 Community edition.

[Return to Download Index](../index.md){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| -------- | ------- | ------------ | ---- | -------- | ---- |
| offline-community-v0.40.0-amd64.tar | v0.40.0 | AMD64 | 12.94 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.40.0-amd64.tar) | 2026-05-15 |
| offline-community-v0.40.0-arm64.tar | v0.40.0 | <font color="green">ARM64</font> | 12.24 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.40.0-arm64.tar) | 2026-05-15 |

## Verification

=== "AMD64"

    ```sh
    echo "eb5192c19e0e9beb8ab474269050ac1d5db0dc89a5e737464cbd8eff7374eda957a7631edc77c3b0b03fa1b257db9040db88b62baf690c421229d26cfdedb11e  offline-community-v0.40.0-amd64.tar" | sha512sum -c
    ```

=== "<font color="green">ARM64</font>"

    ```sh
    echo "ba2bf22c37203c2442bd8f185651ceaa35730e568ac8b5f23f635277e25bc506dd07ed72e8f730f09f8465525d35a1cbf3d0dd02bf970e2871c9e104465e3ffa  offline-community-v0.40.0-arm64.tar" | sha512sum -c
    ```

## Installation

=== "AMD64"

    ```sh
    tar -xvf offline-community-v0.40.0-amd64.tar
    ```

=== "<font color="green">ARM64</font>"

    ```sh
    tar -xvf offline-community-v0.40.0-arm64.tar
    ```

- See [Community Installation Guide](../../install/community/k8s/online.md#_2)
- [Apply for free trial](../../dce/license0.md)

## Modules

| Module | Introduction |
|--------|--------------|
| Global Management | User access control, permissions, workspaces |
| Container Management | Clusters, nodes, workloads |
| Observability | Dashboards, monitoring |

## More

- [Online Docs](../../dce/index.md)
