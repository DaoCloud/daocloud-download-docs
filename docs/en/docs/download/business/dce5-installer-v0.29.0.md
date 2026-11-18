---
MTPE: windsonsea
date: 2025-05-22
hide:
  - navigation
---

# DCE Enterprise with Installer v0.29.0

This page provides downloads for the offline installation package and verification files for DCE Enterprise.

[Return to Download Guide](../index.md#download-dce-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.29.0-amd64.tar | v0.29.0 | AMD 64 | 30.06 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.29.0-amd64.tar) | 2025-05-14 |
| offline-v0.29.0-arm64.tar | v0.29.0 | <font color="green">ARM 64</font> | 26.79 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.29.0-arm64.tar) | 2025-05-14 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "a9182f046b918743ed3dfbfd5403134b9b5e43e8373f34016ffa12af5892678b352d4fa565945e1f39933aecf712754fb2be1d27e44f717a507c506c86a05993  offline-v0.29.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.29.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "4ffa38e50fb7a91d9f47483496e34e004b8852fc2e63069ced6fc236fdfb006f0e00ecaeab1d7e2a64937afba6850ca12a5c1592758e0c6eab731581d3d5b8a5  offline-v0.29.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.29.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.29.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.29.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.36.0](../../ghippo/intro/release-notes.md#v0360) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.39.0](../../kpanda/intro/release-notes.md#v0390) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.36.1](../../insight/intro/release-notes.md#v0361) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.36.0](../../amamba/intro/release-notes.md#v0360) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.46.0](../../skoala/intro/release-notes.md#v0460) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.35.0](../../mspider/intro/release-notes.md#v0350) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.24.1](../../middleware/elasticsearch/release-notes.md#v0241) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.24.0](../../middleware/kafka/release-notes.md#v0240) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.21.1](../../middleware/minio/release-notes.md#v0211) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.26.1](../../middleware/mysql/release-notes.md#v0261) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.27.1](../../middleware/rabbitmq/release-notes.md#v0271) |
| Middleware Redis | An in-memory database caching service. | [v0.27.1](../../middleware/redis/release-notes.md#v0271) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.0](../../kangaroo/intro/release-notes.md#v0240) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.2](../../network/intro/release-notes.md#v0162) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.3](../../storage/hwameistor/release-notes.md#v0162) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.16.1](../../baize/intro/release-notes.md#v0161) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.19.1](../../kant/intro/release-notes.md#v0191) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
