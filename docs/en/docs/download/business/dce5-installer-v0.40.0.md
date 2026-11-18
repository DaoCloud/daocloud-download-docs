---
MTPE: windsonsea
date: 2026-09-30
hide:
  - navigation
---

# DCE Enterprise with Installer v0.40.0

This page provides offline installation packages and checksum files for DCE Enterprise edition.

[Return to Download Index](../index.md#download-dce-enterprise){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| -------- | ------- | ------------ | ---- | -------- | ---- |
| offline-v0.40.0-amd64.tar | v0.40.0 | AMD 64 | 35.06 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.40.0-amd64.tar) | 2026-05-15 |
| offline-v0.40.0-arm64.tar | v0.40.0 | <font color="green">ARM 64</font> | 31.66 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.40.0-arm64.tar) | 2026-05-15 |

## Verification

Go to the directory where the offline package is downloaded.

=== "AMD 64"

    Run the following command to verify:

    ```sh
    echo "ce970ee13c534fdebdbaa610087f026d865586a4641bef36cf391321b1d0542ffda89b6b88424d33edc9bc84a712e3d05abf9eabe5ea9309c31236a82cecdc91  offline-v0.40.0-amd64.tar" | sha512sum -c
    ```

    If successful:

    ```none
    offline-v0.40.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify:

    ```sh
    echo "d9c44b69c25bc5e26f4b722bfb6c1d274c7f707edb31af6fbd2e2427c51299a4c6379daa847bf551927117fca15ab0ed4dde14bea81845272bd09476fa087227  offline-v0.40.0-arm64.tar" | sha512sum -c
    ```

    If successful:

    ```none
    offline-v0.40.0-arm64.tar: OK
    ```

## Installation

After verification, extract:

=== "AMD 64"

    ```sh
    tar -xvf offline-v0.40.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    ```sh
    tar -xvf offline-v0.40.0-arm64.tar
    ```

- See [Enterprise Installation Guide](../../install/commercial/start-install.md)
- Contact: info@daocloud.io or 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.46.0](../../ghippo/intro/release-notes.md#v0460) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.46.1](../../kpanda/intro/release-notes.md#v0461) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.41.2](../../insight/intro/release-notes.md#v0412) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.40.1](../../amamba/intro/release-notes.md#v0401) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.55.0](../../skoala/intro/release-notes.md#v0550) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.39.0](../../mspider/intro/release-notes.md#v0390) |
| Device Management | A Kubernetes cloud-native infrastructure management component built for intelligent computing centers, enabling unified management of hardware resources such as hosts and switches. | [v0.6.0](../../topohub/intro/release-notes.md#v060) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.28.0](../../middleware/elasticsearch/release-notes.md#v0280) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.30.0](../../middleware/kafka/release-notes.md#v0300) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.25.0](../../middleware/minio/release-notes.md#v0250) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.30.1](../../middleware/mysql/release-notes.md#v0301) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.32.0](../../middleware/rabbitmq/release-notes.md#v0310) |
| Middleware Redis | An in-memory database caching service. | [v0.31.0](../../middleware/redis/release-notes.md#v0300) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.6](../../network/intro/release-notes.md#v0166) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.0.2](../../storage/hwameistor/release-notes.md#v102) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.26.0](../../baize/intro/release-notes.md#v0260) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.14.0](../../hydra/intro/release-notes.md#v0140) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.22.0](../../kant/intro/release-notes.md#v0220) |

## More

- [Online Docs](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
