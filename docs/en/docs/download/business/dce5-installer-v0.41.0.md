---
MTPE: windsonsea
date: 2026-09-30
hide:
  - navigation
---

# DCE Enterprise with Installer v0.41.0

This page provides offline installation packages and checksum files for DCE Enterprise edition.

[Return to Download Index](../index.md#download-dce-enterprise){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| -------- | ------- | ------------ | ---- | -------- | ---- |
| offline-v0.41.0-amd64.tar | v0.41.0 | AMD 64 | 35.13 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.41.0-amd64.tar) | 2026-06-08 |
| offline-v0.41.0-arm64.tar | v0.41.0 | <font color="green">ARM 64</font> | 31.64 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.41.0-arm64.tar) | 2026-06-08 |

## Verification

Go to the directory where the offline package is downloaded.

=== "AMD 64"

    Run the following command to verify:

    ```sh
    echo "3ff7330d0950b93e4ebb9cf04af72b8ca0a886faaf034470b00b9ffbb69bc34105ecd19993eda951d9edcb7d1bb95d69a8b2398277ff41492f145aa3bb77efd7  offline-v0.41.0-amd64.tar" | sha512sum -c
    ```

    If successful:

    ```none
    offline-v0.41.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify:

    ```sh
    echo "6e953fbfdd19fe7683c8af0e8a899e7a56dc747bc942572d3b71726f29d7abcef4ae19d5db325872daf9408b791f68a919b5baec6b2e1647fc7faef8cd9c2c91  offline-v0.41.0-arm64.tar" | sha512sum -c
    ```

    If successful:

    ```none
    offline-v0.41.0-arm64.tar: OK
    ```

## Installation

After verification, extract:

=== "AMD 64"

    ```sh
    tar -xvf offline-v0.41.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    ```sh
    tar -xvf offline-v0.41.0-arm64.tar
    ```

- See [Enterprise Installation Guide](../../install/commercial/start-install.md)
- Contact: info@daocloud.io or 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.46.0](../../ghippo/intro/release-notes.md#v0460) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.47.0](../../kpanda/intro/release-notes.md#v0470) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.42.0](../../insight/intro/release-notes.md#v0420) |
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
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.25.0](../../kangaroo/intro/release-notes.md#v0250) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.6](../../network/intro/release-notes.md#v0166) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.0.2](../../storage/hwameistor/release-notes.md#v102) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.27.0](../../baize/intro/release-notes.md#v0260) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.15.0](../../hydra/intro/release-notes.md#v0140) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.22.0](../../kant/intro/release-notes.md#v0220) |

## More

- [Online Docs](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
