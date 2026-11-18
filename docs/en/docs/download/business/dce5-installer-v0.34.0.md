---
MTPE: windsonsea
date: 2025-09-08
hide:
  - navigation
---

# DCE Enterprise with Installer v0.34.0

This page provides downloads for the offline installation package and verification files for DCE Enterprise.

[Return to Download Guide](../index.md#download-dce-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.34.0-amd64.tar | v0.34.0 | AMD 64 | 33.88 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.34.0-amd64.tar) | 2025-10-15 |
| offline-v0.34.0-arm64.tar | v0.34.0 | <font color="green">ARM 64</font> | 30.76 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.34.0-arm64.tar) | 2025-10-15 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "69204f273e94487f1e3440de831f8fa160b6196ee27ed80f2094127aea57016ecca30cebb7a4726820a0b76c1c1a7cc94c4d1d69d911bdef350384c30a42f76e  offline-v0.34.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.34.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "16074fb59ef5c4742fe87f6f3fb0b78fe2eca46f3536ed06851ef9f66ad26a77e684aafb981c44cac1066229478480028bef91d7a8bb05624104d30f74b0b839  offline-v0.34.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.34.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.34.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.34.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.41.0](../../ghippo/intro/release-notes.md#v0410) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.43.0](../../kpanda/intro/release-notes.md#v0430) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.38.2](../../insight/intro/release-notes.md#v0382) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.38.0](../../amamba/intro/release-notes.md#v0380) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.49.0](../../skoala/intro/release-notes.md#v0490) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.36.3](../../mspider/intro/release-notes.md#v0363) |
| Device Management | A Kubernetes cloud-native infrastructure management component built for intelligent computing centers, enabling unified management of hardware resources such as hosts and switches. | [v0.4.1](../../topohub/intro/release-notes.md#v041) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.25.2](../../middleware/elasticsearch/release-notes.md#v0252) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.25.0](../../middleware/kafka/release-notes.md#v0250) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.21.1](../../middleware/minio/release-notes.md#v0211) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.27.1](../../middleware/mysql/release-notes.md#v0271) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.27.3](../../middleware/rabbitmq/release-notes.md#v0273) |
| Middleware Redis | An in-memory database caching service. | [v0.28.0](../../middleware/redis/release-notes.md#v0280) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.5](../../network/intro/release-notes.md#v0165) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.5](../../storage/hwameistor/release-notes.md#v0165) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.21.1](../../baize/intro/release-notes.md#v0211) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.10.0](../../insight/intro/release-notes.md#v0100) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.21.0](../../kant/intro/release-notes.md#v0210) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
