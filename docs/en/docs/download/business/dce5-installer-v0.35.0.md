---
MTPE: windsonsea
date: 2025-11-10
hide:
  - navigation
---

# DCE Enterprise with Installer v0.35.0

This page provides downloads for the offline installation package and verification files for DCE Enterprise.

[Return to Download Guide](../index.md#download-dce-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.35.0-arm64.tar | v0.35.0 | <font color="green">ARM 64</font> | 31.14 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.35.0-arm64.tar) | 2025-11-10 |
| offline-v0.35.0-amd64.tar | v0.35.0 | AMD 64 | 34.40 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.35.0-amd64.tar) | 2025-11-10 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "3b2e24f2b10e56c9cce257ea74e25aec2fd5bd7db33c3b97a64796fb218eccdf6329c1984619dfddbcd62ab3439410bb78b1f6cc7c169f211a1b3d8cf9f927b0  offline-v0.35.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.35.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "2d2e921311b709fe2c3bf7166ce86fff5758dcbef870cdaba3e2d5043a57f119820afaff8dde869002f8fffca5605243c295aebd475a5aec553437a674497be9  offline-v0.35.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.35.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.35.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.35.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.42.2](../../ghippo/intro/release-notes.md#v0422) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.43.1](../../kpanda/intro/release-notes.md#v0431) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.39.0](../../insight/intro/release-notes.md#v0390) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.38.1](../../amamba/intro/release-notes.md#v0381) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.50.1](../../skoala/intro/release-notes.md#v0501) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.37.0](../../mspider/intro/release-notes.md#v0370) |
| Device Management | A Kubernetes cloud-native infrastructure management component built for intelligent computing centers, enabling unified management of hardware resources such as hosts and switches. | [v0.5.0](../../topohub/intro/release-notes.md#v050) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.25.2](../../middleware/elasticsearch/release-notes.md#v0252) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.26.0](../../middleware/kafka/release-notes.md#v0260) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.22.0](../../middleware/minio/release-notes.md#v0220) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.27.1](../../middleware/mysql/release-notes.md#v0271) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.28.0](../../middleware/rabbitmq/release-notes.md#v0280) |
| Middleware Redis | An in-memory database caching service. | [v0.28.0](../../middleware/redis/release-notes.md#v0280) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.5](../../network/intro/release-notes.md#v0165) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.5](../../storage/hwameistor/release-notes.md#v0165) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.22.0](../../baize/intro/release-notes.md#v0220) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.11.0](../../hydra/intro/release-notes.md#v0110) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.21.0](../../kant/intro/release-notes.md#v0210) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
