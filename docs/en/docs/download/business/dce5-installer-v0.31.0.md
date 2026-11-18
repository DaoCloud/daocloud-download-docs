---
MTPE: windsonsea
date: 2026-09-30
hide:
  - navigation
---

# DCE Enterprise with Installer v0.31.0

This page provides downloads for the offline installation package and verification files for DCE Enterprise.

[Return to Download Guide](../index.md#download-dce-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.31.0-amd64.tar | v0.31.0 | AMD 64 | 32.95 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.31.0-amd64.tar) | 2025-07-07 |
| offline-v0.31.0-arm64.tar | v0.31.0 | <font color="green">ARM 64</font> | 29.99 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.31.0-arm64.tar) | 2025-07-07 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "6d5a62c50e04449334835375665dbaa0d192d20c8c6b2ea2c6d73a3573130c99e26ef6efe00090b0097effc960bdc01aea3f7866ef8fcb43a5e86fcafbef65fa  offline-v0.31.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.31.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "00d63291644014154dc55b13ac8f8d64d8020b4019f002595a80875da5cb270a909104042c5f75731b508138a793c6428682a884d71813e0935f3fffea8a53f7  offline-v0.31.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.31.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.31.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.31.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.38.0](../../ghippo/intro/release-notes.md#v0380) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.40.1](../../kpanda/intro/release-notes.md#v0401) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.37.0](../../insight/intro/release-notes.md#v0370) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.37.0](../../amamba/intro/release-notes.md#v0370) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.47.1](../../skoala/intro/release-notes.md#v0471) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.35.2](../../mspider/intro/release-notes.md#v0352) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.24.2](../../middleware/elasticsearch/release-notes.md#v0242) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.24.2](../../middleware/kafka/release-notes.md#v0242) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.21.1](../../middleware/minio/release-notes.md#v0211) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.26.3](../../middleware/mysql/release-notes.md#v0262) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.27.2](../../middleware/rabbitmq/release-notes.md#v0272) |
| Middleware Redis | An in-memory database caching service. | [v0.27.2](../../middleware/redis/release-notes.md#v0272) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.3](../../network/intro/release-notes.md#v0163) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.4](../../storage/hwameistor/release-notes.md) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.16.1](../../baize/intro/release-notes.md#v0161) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.20.0](../../kant/intro/release-notes.md#v0200) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
