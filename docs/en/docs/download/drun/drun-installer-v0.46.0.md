---
MTPE: windsonsea
date: 2026-11-12
hide:
  - navigation
---

# d.run AI OS v0.46.0

This page provides offline installation packages and checksum files for d.run AI OS.

[Return to Download Index](../index.md#download-drun-ai-os){ .md-button } [More Historical Versions](./index.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.46.0-amd64.tar | v0.46.0 | AMD 64 | 44.76 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.46.0-amd64.tar) | 2026-11-12 |
| offline-v0.46.0-arm64.tar | v0.46.0 | <font color="green">ARM 64</font> | 41.45 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.46.0-arm64.tar) | 2026-11-12 |

## Verification

Go to the directory where the offline installation package is downloaded.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "19f9ef1f105dfe3636eac347c48a7ade67fdd676bd9f453340e99191006962efe95c8c990368d6e1986838e5349383bb901f9a6489effccf4c0ee903fcab5d0a  offline-v0.46.0-amd64.tar" | sha512sum -c
    ```

    A successful verification prints:

    ```none
    offline-v0.46.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "7bb70766597461581ea640db4ca8686884d11c6d1b7a24164c4af40837353dfc189da651bcb574c15c18a45e095e789c0e1dcb17727d1e98fac53139156613ff  offline-v0.46.0-arm64.tar" | sha512sum -c
    ```

    A successful verification prints:

    ```none
    offline-v0.46.0-arm64.tar: OK
    ```

## Installation

After verifying the offline package:

=== "AMD 64"

    Run the following command to extract the tarball:

    ```sh
    tar -zxvf offline-v0.46.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to extract the tarball:

    ```sh
    tar -zxvf offline-v0.46.0-arm64.tar
    ```

- For installation instructions, see [Offline Install d.run AI OS](https://docs.daocloud.io/en/drun/install/start-install/).
- Contact: info@daocloud.io or 400 002 6898

## Modules

d.run AI OS includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| ClawOS | 多智能体运行和治理平台 | [v0.7.1](../../drun/clawos/workspace/index.md) |
| 大模型服务平台 | 提供从模型部署到运维管理的全生命周期服务，帮助企业和开发者高效地接入和使用各类大模型能力 | [v0.20.0](../../hydra/intro/release-notes.md#v0200) |
| AI Lab | 训推一体化平台，算力资源统一调度，简化 AI 应用开发和部署 | [v0.31.1](../../baize/intro/release-notes.md#v0311) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.51.0](../../kpanda/intro/release-notes.md#v0510) |
| 设备管理 | 面向智算中心打造的 Kubernetes 云原生基础设施管理组件，能够统一管理主机、交换机等硬件资源 | [v0.17.0](../../topohub/intro/release-notes.md#v0170) |
| 镜像仓库 | 用于存储 K8s、DevOps 和容器应用开发的镜像 | [v0.26.0](../../kangaroo/intro/release-notes.md) |
| 云原生网络 | 针对不同的 Linux 内核，支持多种 CNI 组合方案 | [v0.19.2](../../network/intro/release-notes.md) |
| 云原生存储 | 提供统一数据存储服务，支持文件、对象、块、本地存储，轻松接入存储厂商方案 | [v1.1.1](../../storage/hwameistor/release-notes.md) |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.51.0](../../ghippo/intro/release-notes.md#v0510) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.45.1](../../insight/intro/release-notes.md#v0451) |

## More

- [Online Docs](../../index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
