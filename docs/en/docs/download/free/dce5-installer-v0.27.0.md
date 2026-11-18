---
MTPE: windsonsea
date: 2025-04-07
hide:
  - navigation
---

# DCE Community with Installer v0.27.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.27.0-amd64.tar | v0.27.0 | AMD 64 | 9.72 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.27.0-amd64.tar) | 2025-03-12 |
| offline-community-v0.27.0-arm64.tar | v0.27.0 | <font color="green">ARM 64</font> | 9.23 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.27.0-arm64.tar) | 2025-03-12 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "60de885a109892167f4fe9bbb6b17d59ca0548fb27eaebeb3704d49f7d8a0e9aa49008a903d4656682704e431eb5618204a81032fa30cc01fba2249750f27c22  offline-community-v0.27.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.27.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "f1f830e43b876f9e32bb56a5c799a9cf8d9c688c8d24ce8b4f2509822d456607c70f121c13cdab55f9a1e71bdd1a96f9509b260a83a814d10c6b0bd8eafcdb9e  offline-community-v0.27.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.27.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.27.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.27.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.35.0](../../ghippo/intro/release-notes.md#v0350) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.37.0](../../kpanda/intro/release-notes.md#v0370) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.35.1](../../insight/intro/release-notes.md#v0351) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
