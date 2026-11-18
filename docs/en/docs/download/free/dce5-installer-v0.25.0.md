---
MTPE: windsonsea
date: 2025-01-10
hide:
  - navigation
---

# DCE Community with Installer v0.25.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.25.0-amd64.tar | v0.25.0 | AMD 64 | 8.53 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.25.0-amd64.tar) | 2025-01-10 |
| offline-community-v0.25.0-arm64.tar | v0.25.0 | <font color="green">ARM 64</font> | 8.16 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.25.0-arm64.tar) | 2025-01-10 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "a41fc508be387a1efa3b7bb1185a58dfe927dc4ee7b84af3aba29e3366e92bd956431b8fd8e8570f22da5daeb86a96e4daad779a2a94bb737dac34d762b0e856  offline-community-v0.25.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.25.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "69c88d275e87ca71dffb1fae242d3abab9841a4728fd200571bd7f4a325c764e811dcfb8219588f305767f05f04375be42e842466685fdc2cbe3df779b41221a  offline-community-v0.25.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.25.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.25.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.25.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.33.0](../../ghippo/intro/release-notes.md#v0330) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.35.0](../../kpanda/intro/release-notes.md#v0350) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.34.0](../../insight/intro/release-notes.md#v0340) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
