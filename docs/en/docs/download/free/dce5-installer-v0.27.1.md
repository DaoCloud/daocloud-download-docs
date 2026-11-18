---
MTPE: windsonsea
date: 2025-04-11
hide:
  - navigation
---

# DCE Community with Installer v0.27.1

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.27.1-amd64.tar | v0.27.1 | AMD 64 | 9.50 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.27.1-amd64.tar) | 2025-04-11 |
| offline-community-v0.27.1-arm64.tar | v0.27.1 | <font color="green">ARM 64</font> | 8.99 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.27.1-arm64.tar) | 2025-04-11 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "c48356ee72102cb4ce821f9da6ee26db19672d88e87e681a2eb396957ab52c59206041ca25284bd3bb0c56058b93dac1ef5f1d8dfda316db45918b2ecb0975f5  offline-community-v0.27.1-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.27.1-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "c55fe39fb564899337ea9535ee51f285f525432025780c5bd4ce82640196d821c8a8c16ba1e54c193a20798f6d1d3b449347c149dfab0b2dbf00d45e06b8ef28  offline-community-v0.27.1-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.27.1-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.27.1-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.27.1-arm64.tar
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
