---
MTPE: windsonsea
date: 2026-01-26
hide:
  - navigation
---

# DCE Enterprise with Installer v0.37.0

This page provides downloads for the offline installation package and verification files for DCE Enterprise.

[Return to Download Guide](../index.md#download-dce-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.37.0-amd64.tar | v0.37.0 | AMD 64 | 34.55 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.37.0-amd64.tar) | 2026-01-12 |
| offline-v0.37.0-arm64.tar | v0.37.0 | <font color="green">ARM 64</font> | 31.26 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.37.0-arm64.tar) | 2026-01-12 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "3fb9d775a06fbd0ca3fc04169f615a29efe6aac417cdaf9e838750b73882c32f4048f566b890a97619209ce41bec80dd7d913dfbea9be587f9a90d54cc899aa7  offline-v0.37.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.37.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "e319d8c42d04d1debcad3a04ce4e6e33882cb5faa34680e786febd16e23719e3b3ef5c5cb39d73242a30278604dfd2d5c71bbb4acebe4a74570a6365164eaa1b  offline-v0.37.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.37.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.37.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.37.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.44.0](../../ghippo/intro/release-notes.md#v0440) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.44.0](../../kpanda/intro/release-notes.md#v0440) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.40.0](../../insight/intro/release-notes.md#v0400) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.39.2](../../amamba/intro/release-notes.md#v0392) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.52.1](../../skoala/intro/release-notes.md#v0521) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.37.0](../../mspider/intro/release-notes.md#v0370) |
| Device Management | A Kubernetes cloud-native infrastructure management component built for intelligent computing centers, enabling unified management of hardware resources such as hosts and switches. | [v0.6.0](../../topohub/intro/release-notes.md#v060) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.26.1](../../middleware/elasticsearch/release-notes.md#v0261) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.28.0](../../middleware/kafka/release-notes.md#v0280) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.23.1](../../middleware/minio/release-notes.md#v0231) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.28.1](../../middleware/mysql/release-notes.md#v0281) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.29.0](../../middleware/rabbitmq/release-notes.md#v0290) |
| Middleware Redis | An in-memory database caching service. | [v0.29.1](../../middleware/redis/release-notes.md#v0291) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.6](../../network/intro/release-notes.md#v0166) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.0.1](../../storage/hwameistor/release-notes.md#v101) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.23.1](../../baize/intro/release-notes.md#v0231) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.12.1](../../hydra/intro/release-notes.md#v0121) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.22.0](../../kant/intro/release-notes.md#v0220) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
