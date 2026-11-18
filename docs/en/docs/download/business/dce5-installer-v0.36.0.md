---
MTPE: windsonsea
date: 2025-12-09
hide:
  - navigation
---

# DCE Enterprise with Installer v0.36.0

This page provides downloads for the offline installation package and verification files for DCE Enterprise.

[Return to Download Guide](../index.md#download-dce-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.36.0-arm64.tar | v0.36.0 | <font color="green">ARM 64</font> | 31.18 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.36.0-arm64.tar) | 2025-12-09 |
| offline-v0.36.0-amd64.tar | v0.36.0 | AMD 64 | 34.44 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.36.0-amd64.tar) | 2025-12-09 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "f59c90f700582e65c6d92c67f8703999347349c9aeaea5ec56dd6c2f1a308e516ac756156e93b6c02f5a91e851c856115f04f5b391ea443dce1783fc29305570  offline-v0.36.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.36.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "a90e559ac83b82a4cfdfcbde62160cd926dfd2b8c296c748a53077f3cc94de1e117c4b0dd89365624dbb1c38c73f589d5334375f111f5f6f7fba1998ea7404d9  offline-v0.36.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.36.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.36.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.36.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.43.0](../../ghippo/intro/release-notes.md#v0430) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.43.3](../../kpanda/intro/release-notes.md#v0433) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.39.2](../../insight/intro/release-notes.md#v0392) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.39.0](../../amamba/intro/release-notes.md#v0390) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.51.0](../../skoala/intro/release-notes.md#v0510) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.37.0](../../mspider/intro/release-notes.md#v0370) |
| Device Management | A Kubernetes cloud-native infrastructure management component built for intelligent computing centers, enabling unified management of hardware resources such as hosts and switches. | [v0.5.0](../../topohub/intro/release-notes.md#v050) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.26.0](../../middleware/elasticsearch/release-notes.md#v0260) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.27.0](../../middleware/kafka/release-notes.md#v0270) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.23.0](../../middleware/minio/release-notes.md#v0230) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.28.0](../../middleware/mysql/release-notes.md#v0280) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.29.0](../../middleware/rabbitmq/release-notes.md#v0290) |
| Middleware Redis | An in-memory database caching service. | [v0.29.0](../../middleware/redis/release-notes.md#v0280) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.6](../../network/intro/release-notes.md#v0166) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.5](../../storage/hwameistor/release-notes.md#v0165) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.23.0](../../baize/intro/release-notes.md#v0230) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.12.1](../../hydra/intro/release-notes.md#v0121) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.21.0](../../kant/intro/release-notes.md#v0210) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
