---
date: 2026-11-12
hide:
  - navigation
---

# DCE 社区版 v0.46.0

本页可下载 DCE 社区版的离线安装包和校验文件。

[返回下载导览页](../index.md#dce){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.46.0-amd64.tar | v0.46.0 | AMD 64 | 7.78 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.46.0-amd64.tar) | 2026-11-12 |
| offline-community-v0.46.0-arm64.tar | v0.46.0 | <font color="green">ARM 64</font> | 7.27 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.46.0-arm64.tar) | 2026-11-12 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "84d311af9119396ebba8b6f32ce116b26ebb562190c5c46a4a70c8923c7b8efc7d31dcb5caa4f6986a9ab08ae5df08ce45eb6bf380a1ef84a7d9aae720f49651  offline-community-v0.46.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.46.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "c2ddbd96cf0e73c1fa41f87370cc9c0137075bd6eb1733613781f151c44611537711e6dff74724ed5f6b6842a2f60224a1ce680d49dd8664dd5b049cfb80d844  offline-community-v0.46.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.46.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.46.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.46.0-arm64.tar
    ```

- 安装请参阅[社区版安装流程](../../install/community/k8s/online.md#_2)
- 成功安装之后请[申请免费社区体验](../../dce/license0.md)

## 模块

DCE 社区版默认包含以下模块：

| 模块     | 介绍            | 最新动态         |
| -------- | -------------- | -------------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.51.0](../../ghippo/intro/release-notes.md#v0510) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.51.0](../../kpanda/intro/release-notes.md#v0510) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.45.1](../../insight/intro/release-notes.md#v0451) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
