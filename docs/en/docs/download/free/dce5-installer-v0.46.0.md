---
MTPE: windsonsea
date: 2026-11-12
hide:
  - navigation
---

# DCE Community with Installer v0.46.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md#download-dce-community){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.46.0-amd64.tar | v0.46.0 | AMD 64 | 7.78 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.46.0-amd64.tar) | 2026-11-12 |
| offline-community-v0.46.0-arm64.tar | v0.46.0 | <font color="green">ARM 64</font> | 7.27 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.46.0-arm64.tar) | 2026-11-12 |

## Verification

Go to the directory where the offline installation package is downloaded.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "84d311af9119396ebba8b6f32ce116b26ebb562190c5c46a4a70c8923c7b8efc7d31dcb5caa4f6986a9ab08ae5df08ce45eb6bf380a1ef84a7d9aae720f49651  offline-community-v0.46.0-amd64.tar" | sha512sum -c
    ```

    A successful verification prints:

    ```none
    offline-community-v0.46.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "c2ddbd96cf0e73c1fa41f87370cc9c0137075bd6eb1733613781f151c44611537711e6dff74724ed5f6b6842a2f60224a1ce680d49dd8664dd5b049cfb80d844  offline-community-v0.46.0-arm64.tar" | sha512sum -c
    ```

    A successful verification prints:

    ```none
    offline-community-v0.46.0-arm64.tar: OK
    ```

## Installation

After verifying the offline package:

=== "AMD 64"

    Run the following command to extract the tarball:

    ```sh
    tar -zxvf offline-community-v0.46.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to extract the tarball:

    ```sh
    tar -zxvf offline-community-v0.46.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Description | Versions |
| -------- | -------------- | -------------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.51.0](../../ghippo/intro/release-notes.md#v0510) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.51.0](../../kpanda/intro/release-notes.md#v0510) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.45.1](../../insight/intro/release-notes.md#v0451) |

## More

- [Online Docs](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
