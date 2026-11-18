---
MTPE: windsonsea
date: 2026-11-12
hide:
  - navigation
---

# DCE Enterprise with Installer v0.46.0

This page provides offline installation packages and checksum files for DCE Enterprise edition.

[Return to Download Index](../index.md#download-dce-enterprise){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

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

- See [Enterprise Installation Guide](../../install/commercial/start-install.md)
- Contact: info@daocloud.io or 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.51.0](../../ghippo/intro/release-notes.md#v0510) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.51.0](../../kpanda/intro/release-notes.md#v0510) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.45.1](../../insight/intro/release-notes.md#v0451) |
| 应用工作台 | 基于容器的 DevOps 应用平台，支持 Jenkins, Tekton, GitOps 等流水线作业 | [v0.42.0](../../amamba/intro/release-notes.md#v0420) |
| 多云编排 | 集中管理多云、混合云、跨云资源的应用编排，具备多云灾备、故障恢复等能力 | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| 微服务引擎 | 提供注册发现、服务治理、配置管理、微服务网关等治理能力 | [v0.57.3](../../skoala/intro/release-notes.md#v0573) |
| 服务网格 | 基于 Istio 开源技术构建的面向云原生应用的下一代服务网格 | [v0.40.0](../../mspider/intro/release-notes.md#v0400) |
| 中间件 Elasticsearch | 目前首选的全文搜索引擎 | [v0.29.0](../../middleware/elasticsearch/release-notes.md#v0290) |
| 中间件 Kafka | 基于开源软件 Kafka 提供的分布式消息队列服务 | [v0.31.0](../../middleware/kafka/release-notes.md#v0310) |
| 中间件 MinIO | 一款非常热门的轻量、开源对象存储方案 | [v0.26.0](../../middleware/minio/release-notes.md#v0260) |
| 中间件 MySQL | 应用最广泛的开源关系数据库 | [v0.31.0](../../middleware/mysql/release-notes.md#v0310) |
| 中间件 RabbitMQ | 实现了高级消息队列协议 (AMQP) 的开源消息代理软件 | [v0.34.0](../../middleware/rabbitmq/release-notes.md#v0340) |
| 中间件 Redis | 一款内存数据库缓存服务 | [v0.31.2](../../middleware/redis/release-notes.md#v0312) |
| 镜像仓库 | 用于存储 K8s、DevOps 和容器应用开发的镜像 | [v0.26.0](../../kangaroo/intro/release-notes.md) |
| 网络 | 针对不同的 Linux 内核，支持多种 CNI 组合方案 | [v0.19.2](../../network/intro/release-notes.md) |
| 存储 | 提供统一数据存储服务，支持文件、对象、块、本地存储，轻松接入存储厂商方案 | [v1.1.1](../../storage/hwameistor/release-notes.md) |

## More

- [Online Docs](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
