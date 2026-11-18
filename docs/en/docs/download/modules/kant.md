---
MTPE: windsonsea
date: 2024-01-09
hide:
  - toc
---

# Cloud Edge Collaboration

This page provides offline packages for different versions of the Cloud Edge Collaboration module.

!!! tip

    `kant` is the internal dev code for cloud edge collaboration.

## Download Edge Components

These edge component offline pacakges are used when joinning edge nodes.

- `keadm_init.sh`: This shell script used to initialize the offline environment, decompress the offline package and copy the decompressed files to the specified working directory.
- `keadm_{arch}.tar.gz`: This tar.gz package contains the KubeEdge installation tool keadm, which is used to install EdgeCore on edge nodes.
- `keadm_containerd_{arch}.tar.gz`: This tar.gz package contains the KubeEdge installation tool keadm and the default version of containerd, which is used to install EdgeCore on edge nodes with default container runtime.

| Package | Architecture | Size | Checksum | Date |
| ------- | ----- | --------- | ---------- | ---- |
| [:arrow_down: keadm_init.sh](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_init.sh) | AMD 64 / <font color="green">ARM 64</font> | 2.31 KB | [:arrow_down: keadm_init_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_init_checksum.sha512sum) | 2025-12-26 |
| [:arrow_down: keadm_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_amd64.tar.gz) | AMD 64 | 31.40 MB | [:arrow_down: keadm_amd64.tar.gz_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_amd64.tar.gz_checksum.sha512sum) | 2025-12-26 |
| [:arrow_down: keadm_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_arm64.tar.gz) | <font color="green">ARM 64</font> | 55.78 MB | [:arrow_down: keadm_arm64.tar.gz_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_arm64.tar.gz_checksum.sha512sum) | 2025-12-26 |
| [:arrow_down: keadm_containerd_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_containerd_amd64.tar.gz) | AMD 64 | 158.69 MB | [:arrow_down: keadm_containerd_amd64.tar.gz_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_containerd_amd64.tar.gz_checksum.sha512sum) | 2025-12-26 |
| [:arrow_down: keadm_containerd_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_containerd_arm64.tar.gz) | <font color="green">ARM 64</font> | 163.86 MB | [:arrow_down: keadm_containerd_arm64.tar.gz_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_containerd_arm64.tar.gz_checksum.sha512sum) | 2025-12-26 |

## Download Cloud Components

| Version | Architecture | Size | Package | Checksum | Date |
| ------- | ----- | -------- | ---------- | -------- | ---- |
| [v0.22.0](../../kant/intro/release-notes.md) | AMD 64 | 177.30 MB | [:arrow_down: kant_v0.22.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.22.0_amd64.tar) | [:arrow_down: kant_v0.22.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.22.0_amd64_checksum.sha512sum) | 2025-12-26 |
| [v0.22.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 169.66 MB | [:arrow_down: kant_v0.22.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.22.0_arm64.tar) | [:arrow_down: kant_v0.22.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.22.0_arm64_checksum.sha512sum) | 2025-12-26 |
| [v0.21.0](../../kant/intro/release-notes.md) | AMD 64 | 171.45 MB | [:arrow_down: kant_v0.21.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.21.0_amd64.tar) | [:arrow_down: kant_v0.21.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.21.0_amd64_checksum.sha512sum) | 2025-09-25 |
| [v0.21.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 164.02 MB | [:arrow_down: kant_v0.21.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.21.0_arm64.tar) | [:arrow_down: kant_v0.21.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.21.0_arm64_checksum.sha512sum) | 2025-09-25 |
| [v0.20.0](../../kant/intro/release-notes.md) | AMD 64 | 168.19 MB | [:arrow_down: kant_v0.20.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.20.0_amd64.tar) | [:arrow_down: kant_v0.20.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.20.0_amd64_checksum.sha512sum) | 2025-06-23 |
| [v0.20.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 160.84 MB | [:arrow_down: kant_v0.20.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.20.0_arm64.tar) | [:arrow_down: kant_v0.20.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.20.0_arm64_checksum.sha512sum) | 2025-06-23 |

??? note "Click to view historical releases"

    | Version | Architecture | Size | Package | Checksum | Date | Notes |
    | ------- | ----- | ---------- | ------------- | ------------- | ----------- | ---- |
    | [v0.19.1](../../kant/intro/release-notes.md) | AMD 64 | 107 MB | [:arrow_down: kant_v0.19.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.19.1_amd64.tar) | [:arrow_down: kant_v0.19.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.19.1_amd64_checksum.sha512sum) | 2025-03-31 | the cloud amd installation package |
    | [v0.19.1](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 103 MB | [:arrow_down: kant_v0.19.1_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.19.1_arm64.tar) | [:arrow_down: kant_v0.19.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.19.1_arm64_checksum.sha512sum) | 2025-03-31 | the cloud arm installation package |
    | [v0.19.1](../../kant/intro/release-notes.md) | AMD 64 | 15 MB | [:arrow_down: kantadm_v0.19.1_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.19.1_amd64.tar.gz) | [:arrow_down: kantadm_v0.19.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.19.1_amd64_checksum.sha512sum) | 2025-03-31 | the edge amd installation package |
    | [v0.19.1](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 13 MB | [:arrow_down: kantadm_v0.19.1_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.19.1_arm64.tar.gz) | [:arrow_down: kantadm_v0.19.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.19.1_arm64_checksum.sha512sum) | 2025-03-31 | the edge arm installation package |
    | [v0.18.0](../../kant/intro/release-notes.md) | AMD 64 | 107 MB | [:arrow_down: kant_v0.18.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.18.0_amd64.tar) | [:arrow_down: kant_v0.18.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.18.0_amd64_checksum.sha512sum) | 2024-12-30 | the cloud amd installation package |
    | [v0.18.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 103 MB | [:arrow_down: kant_v0.18.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.18.0_arm64.tar) | [:arrow_down: kant_v0.18.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.18.0_arm64_checksum.sha512sum) | 2024-12-30 | the cloud arm installation package |
    | [v0.18.0](../../kant/intro/release-notes.md) | AMD 64 | 15 MB | [:arrow_down: kantadm_v0.18.0_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_amd64.tar.gz) | [:arrow_down: kantadm_v0.18.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_amd64_checksum.sha512sum) | 2024-12-30 | the edge amd installation package |
    | [v0.18.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 13 MB | [:arrow_down: kantadm_v0.18.0_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_arm64.tar.gz) | [:arrow_down: kantadm_v0.18.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_arm64_checksum.sha512sum) | 2024-12-30 | the edge arm64 installation package |
    | [v0.18.0](../../kant/intro/release-notes.md) | <font color="green">ARM 32</font> | 14 MB | [:arrow_down: kantadm_v0.18.0_arm.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_arm.tar.gz) | [:arrow_down: kantadm_v0.18.0_arm_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_arm_checksum.sha512sum) | 2024-12-30 | the edge arm installation package |
    | [v0.17.0](../../kant/intro/release-notes.md) | AMD 64 | 107 MB | [:arrow_down: kant_v0.17.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.17.0_amd64.tar) | [:arrow_down: kant_v0.17.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.17.0_amd64_checksum.sha512sum) | 2024-11-28 | the cloud amd installation package |
    | [v0.17.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 103 MB | [:arrow_down: kant_v0.17.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.17.0_arm64.tar) | [:arrow_down: kant_v0.17.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.17.0_arm64_checksum.sha512sum) | 2024-11-28 | the cloud arm installation package |
    | [v0.17.0](../../kant/intro/release-notes.md) | AMD 64 | 15 MB | [:arrow_down: kantadm_v0.17.0_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_amd64.tar.gz) | [:arrow_down: kantadm_v0.17.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_amd64_checksum.sha512sum) | 2024-11-28 | the edge amd installation package |
    | [v0.17.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 13 MB | [:arrow_down: kantadm_v0.17.0_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_arm64.tar.gz) | [:arrow_down: kantadm_v0.17.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_arm64_checksum.sha512sum) | 2024-11-28 | the edge arm64 installation package |
    | [v0.17.0](../../kant/intro/release-notes.md) | <font color="green">ARM 32</font> | 14 MB | [:arrow_down: kantadm_v0.17.0_arm.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_arm.tar.gz) | [:arrow_down: kantadm_v0.17.0_arm_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_arm_checksum.sha512sum) | 2024-11-28 | the edge arm installation package |
    | [v0.16.1](../../kant/intro/release-notes.md) | AMD 64 | 107 MB | [:arrow_down: kant_v0.16.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.16.1_amd64.tar) | [:arrow_down: kant_v0.16.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.16.1_amd64_checksum.sha512sum) | 2024-11-04 | the cloud amd installation package |
    | [v0.16.1](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 103 MB | [:arrow_down: kant_v0.16.1_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.16.1_arm64.tar) | [:arrow_down: kant_v0.16.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.16.1_arm64_checksum.sha512sum) | 2024-11-04 | the cloud arm installation package |
    | [v0.16.1](../../kant/intro/release-notes.md) | AMD 64 | 15 MB | [:arrow_down: kantadm_v0.16.1_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_amd64.tar.gz) | [:arrow_down: kantadm_v0.16.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_amd64_checksum.sha512sum) | 2024-11-04 | the edge amd installation package |
    | [v0.16.1](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 13 MB | [:arrow_down: kantadm_v0.16.1_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_arm64.tar.gz) | [:arrow_down: kantadm_v0.16.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_arm64_checksum.sha512sum) | 2024-11-04 | the edge arm64 installation package |
    | [v0.16.1](../../kant/intro/release-notes.md) | <font color="green">ARM 32</font> | 14 MB | [:arrow_down: kantadm_v0.16.1_arm.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_arm.tar.gz) | [:arrow_down: kantadm_v0.16.1_arm_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_arm_checksum.sha512sum) | 2024-11-04 | the edge arm installation package |

## Verification

To verify the integrity of the downloaded offline package and checksum file,
run the following command in the directory:

```sh
echo "$(cat kant_0.6.1_amd64_checksum.sha512sum)" | sha512sum -c
```

Upon successful verification, the result will be similar to:

```none
kant_0.6.1_amd64.tar: ok
```

## Installation

Refer to [offline upgrade of the cloud-edge collaboration module](../../kant/intro/offline-upgrade.md) for installation.
If you have any license key-related questions, please contact the DaoCloud delivery team.
Email info@daocloud.io or call 400 002 6898.
