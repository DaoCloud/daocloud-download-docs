---
date: 2026-11-12
hide:
  - navigation
---

# d.run Token 工厂效能平台 v0.46.0

本页可下载 d.run Token 工厂效能平台的离线安装包和校验文件。

[返回下载导览页](../index.md#drun-token){ .md-button } [更多历史版本](./index.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.46.0-amd64.tar | v0.46.0 | AMD 64 | 44.76 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.46.0-amd64.tar) | 2026-11-12 |
| offline-v0.46.0-arm64.tar | v0.46.0 | <font color="green">ARM 64</font> | 41.45 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.46.0-arm64.tar) | 2026-11-12 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "19f9ef1f105dfe3636eac347c48a7ade67fdd676bd9f453340e99191006962efe95c8c990368d6e1986838e5349383bb901f9a6489effccf4c0ee903fcab5d0a  offline-v0.46.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.46.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "7bb70766597461581ea640db4ca8686884d11c6d1b7a24164c4af40837353dfc189da651bcb574c15c18a45e095e789c0e1dcb17727d1e98fac53139156613ff  offline-v0.46.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.46.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.46.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.46.0-arm64.tar
    ```

- 安装请参阅[离线安装 d.run Token 工厂效能平台](https://docs.daocloud.io/tf/install/start-install/)
- 成功安装之后请联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898

## 模块

d.run Token 工厂效能平台包含以下模块，按需即插即用满足各类应用场景：

| 模块 | 介绍 | 最新动态 |
| ---- | --- | ------ |
| 大模型服务平台 | 提供从模型部署到运维管理的全生命周期服务，帮助企业和开发者高效地接入和使用各类大模型能力 | [v0.20.0](../../hydra/intro/release-notes.md#v0200) |
| 算力云 | 运营算力的平台 | [v0.18.0](../../tf/zestu/index.md) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.51.0](../../kpanda/intro/release-notes.md#v0510) |
| 设备管理 | 面向智算中心打造的 Kubernetes 云原生基础设施管理组件，能够统一管理主机、交换机等硬件资源 | [v0.17.0](../../topohub/intro/release-notes.md#v0170) |
| 镜像仓库 | 用于存储 K8s、DevOps 和容器应用开发的镜像 | [v0.26.0](../../kangaroo/intro/release-notes.md#v0260) |
| 云原生网络 | 针对不同的 Linux 内核，支持多种 CNI 组合方案 | [v0.19.2](../../network/intro/release-notes.md) |
| 云原生存储 | 提供统一数据存储服务，支持文件、对象、块、本地存储，轻松接入存储厂商方案 | [v1.1.1](../../storage/hwameistor/release-notes.md) |
| 费用中心 | 费用和账单管理系统 | [v0.17.0](../../tf/leopard/index.md) |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.51.0](../../ghippo/intro/release-notes.md#v0510) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.45.1](../../insight/intro/release-notes.md#v0451) |

## 更多

- [在线文档](../../index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
