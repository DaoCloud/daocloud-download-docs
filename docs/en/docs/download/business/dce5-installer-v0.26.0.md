---
MTPE: windsonsea
date: 2025-02-13
hide:
  - navigation
---

# DCE Enterprise with Installer v0.26.0

This page provides downloads for the offline installation package and verification files for DCE Enterprise.

[Return to Download Guide](../index.md#download-dce-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ------------ | --------- | -------- | ----------- |
| offline-v0.26.0-amd64.tar | v0.26.0 | AMD 64 | 33.01 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.26.0-amd64.tar) | 2025-02-13 |
| offline-v0.26.0-arm64.tar | v0.26.0 | <font color="green">ARM 64</font> | 29.16 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.26.0-arm64.tar) | 2025-02-13 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "eac3ab8391a7b67fcf739df063e1f3a6c33b9e48720869ace857d1e839cc9a2d539a47110fcbab31a583bca404849d1b291430d5871036fd51f7692b6ff6b113  offline-v0.26.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.26.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "68da5dd9208268b8fe7a30cc2d3f2c6b7ee1785996783f80c56e356f9f67cc61705d49227a087637e7ecad717de639600c0d0feaa8b2bc527d8d5fae79c6d24f  offline-v0.26.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.26.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.26.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.26.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.34.0](../../ghippo/intro/release-notes.md#v0340) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.36.0](../../kpanda/intro/release-notes.md#v0360) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.34.1](../../insight/intro/release-notes.md#v0341) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.34.0](../../amamba/intro/release-notes.md#v0340) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.44.0](../../skoala/intro/release-notes.md#v0440) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.34.0](../../mspider/intro/release-notes.md#v0340) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.23.0](../../middleware/elasticsearch/release-notes.md#v0230) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.22.0](../../middleware/kafka/release-notes.md#v0220) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.21.0](../../middleware/minio/release-notes.md#v0210) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.25.1](../../middleware/mysql/release-notes.md#v0251) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.27.0](../../middleware/rabbitmq/release-notes.md#v0270) |
| Middleware Redis | An in-memory database caching service. | [v0.26.0](../../middleware/redis/release-notes.md#v0260) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.0](../../kangaroo/intro/release-notes.md#v0240) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.2](../../network/intro/release-notes.md#v0162) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.1](../../storage/hwameistor/release-notes.md#v0161) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
