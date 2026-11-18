---
MTPE: windsonsea
date: 2025-02-13
hide:
  - navigation
---

# DCE Community with Installer v0.26.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.26.0-amd64.tar | v0.26.0 | AMD 64 | 8.57 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.26.0-amd64.tar) | 2025-02-13 |
| offline-community-v0.26.0-arm64.tar | v0.26.0 | <font color="green">ARM 64</font> | 8.21 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.26.0-arm64.tar) | 2025-02-13 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "b32454b25963729bbc297b6ea20519deedc2ac8c750f43d7d373b1b0248b7f485d19261a3c8b6f760f3433ef67805a4d1f16460b389a2fbce1c89b300cd88ea0  offline-community-v0.26.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.26.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "f1adf2d9cfe767e3a2b3e5438fb61dbdbbd1d980a00d58b1b15a592ba6ee4462c57c29bd5c113d9fcbd7e6032b18d221cc348f68bd11bc437bd39df06d6a166f  offline-community-v0.26.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.26.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.26.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.26.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.34.0](../../ghippo/intro/release-notes.md#v0340) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.36.0](../../kpanda/intro/release-notes.md#v0360) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.34.1](../../insight/intro/release-notes.md#v0341) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
