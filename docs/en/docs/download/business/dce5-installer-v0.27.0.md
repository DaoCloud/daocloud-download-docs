---
MTPE: windsonsea
date: 2025-04-07
hide:
  - navigation
---

# DCE Enterprise with Installer v0.27.0

This page provides downloads for the offline installation package and verification files for DCE Enterprise.

[Return to Download Guide](../index.md#download-dce-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.27.0-amd64.tar | v0.27.0 | AMD 64 | 29.45 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.27.0-amd64.tar) | 2025-03-12 |
| offline-v0.27.0-arm64.tar | v0.27.0 | <font color="green">ARM 64</font> | 25.93 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.27.0-arm64.tar) | 2025-03-12 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "9b10a525d805937e4cad648a4c05ab1d2086f2711cd8a115d5b90a69710ba3690bb276bb49c2c835109e43f35de1c93eb24defb5525f0a1ad72dffbdaf9c0477  offline-v0.27.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.27.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "039d9c9f84879704b7df87d335cd246cc2f96a3cb1f4d69d77994f48368f447cd5758724aaf6773c094ec000d38cf70ba8e283b288309ba9f8e9d19f9d37aa3c  offline-v0.27.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.27.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.27.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.27.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.35.0](../../ghippo/intro/release-notes.md#v0350) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.37.0](../../kpanda/intro/release-notes.md#v0370) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.35.1](../../insight/intro/release-notes.md#v0351) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.35.0](../../amamba/intro/release-notes.md#v0350) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.45.0](../../skoala/intro/release-notes.md#v0450) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.34.0](../../mspider/intro/release-notes.md#v0340) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.24.0](../../middleware/elasticsearch/release-notes.md#v0240) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.23.0](../../middleware/kafka/release-notes.md#v0230) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.21.0](../../middleware/minio/release-notes.md#v0210) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.26.0](../../middleware/mysql/release-notes.md#v0260) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.27.0](../../middleware/rabbitmq/release-notes.md#v0270) |
| Middleware Redis | An in-memory database caching service. | [v0.27.0](../../middleware/redis/release-notes.md#v0270) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.0](../../kangaroo/intro/release-notes.md#v0240) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.2](../../network/intro/release-notes.md#v0162) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.2](../../storage/hwameistor/release-notes.md#v0162) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
