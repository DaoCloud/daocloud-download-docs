---
MTPE: windsonsea
date: 2025-07-08
hide:
  - navigation
---

# DCE Community with Installer v0.31.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.31.0-amd64.tar | v0.31.0 | AMD 64 | 13.33 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.31.0-amd64.tar) | 2025-07-07 |
| offline-community-v0.31.0-arm64.tar | v0.31.0 | <font color="green">ARM 64</font> | 12.61 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.31.0-arm64.tar) | 2025-07-07 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "35f6e7d93f91e8d091acec0bfc66d9a1a8cf6930a060cb9a18306dd2b692bcb3a7fd52714f5aa930a5da31421d8619a037c4cfe7b992de73094b3b06e10b8dd7  offline-community-v0.31.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.31.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "fcc3ebe2b086374ba8fb74871dbc60439a677aeaa9c10762c533d32648f027fbabc67d83cd4ba52e9a4b49f8c9a78ad3afe123513b3642ed4fd16341b4ee5f70  offline-community-v0.31.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.31.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.31.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.31.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.38.0](../../ghippo/intro/release-notes.md#v0380) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.40.1](../../kpanda/intro/release-notes.md#v0401) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.37.0](../../insight/intro/release-notes.md#v0370) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
