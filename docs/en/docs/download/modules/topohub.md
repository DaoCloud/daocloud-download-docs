---
hide:
  - toc
---

# Device Management

This page provides offline packages for different versions of the device management module.

!!! tip

    `topohub` is the internal dev code for device management.

## Download

| Version  | Architecture | Size | Package | Checksum | Date |
| ---- | ---- | -------- | ------ | -------- | -------- |
| [v0.6.0](../../topohub/intro/release-notes.md) | AMD 64 | 51.91 MB | [:arrow_down: topohub-dashboard_v0.6.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.6.0_amd64.tar) | [:arrow_down: topohub-dashboard_v0.6.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.6.0_amd64_checksum.sha512sum) | 2025-12-26 |
| [v0.6.0](../../topohub/intro/release-notes.md) | <font color="green">ARM 64</font> | 49.36 MB | [:arrow_down: topohub-dashboard_v0.6.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.6.0_arm64.tar) | [:arrow_down: topohub-dashboard_v0.6.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.6.0_arm64_checksum.sha512sum) | 2025-12-26 |
| [v0.5.0](../../topohub/intro/release-notes.md) | AMD 64 | 51.90 MB | [:arrow_down: topohub-dashboard_v0.5.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.5.0_amd64.tar) | [:arrow_down: topohub-dashboard_v0.5.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.5.0_amd64_checksum.sha512sum) | 2025-10-29 |
| [v0.5.0](../../topohub/intro/release-notes.md) | <font color="green">ARM 64</font> | 49.34 MB | [:arrow_down: topohub-dashboard_v0.5.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.5.0_arm64.tar) | [:arrow_down: topohub-dashboard_v0.5.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.5.0_arm64_checksum.sha512sum) | 2025-10-29 |

??? note "Click to view historical releases"

    | Version  | Architecture | Size | Package | Checksum | Date |
    | ---- | ---- | -------- | ------ | -------- | -------- |
    | [v0.4.0](../../topohub/intro/release-notes.md) | AMD 64 | 52.47 MB | [:arrow_down: topohub-dashboard_v0.4.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.4.0_amd64.tar) | [:arrow_down: topohub-dashboard_v0.4.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.4.0_amd64_checksum.sha512sum) | 2025-08-29 |
    | [v0.4.0](../../topohub/intro/release-notes.md) | <font color="green">ARM 64</font> | 49.92 MB | [:arrow_down: topohub-dashboard_v0.4.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.4.0_arm64.tar) | [:arrow_down: topohub-dashboard_v0.4.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.4.0_arm64_checksum.sha512sum) | 2025-08-29 |
    | [v0.3.0](../../topohub/intro/release-notes.md) | AMD 64 | 47.89 MB | [:arrow_down: topohub_v0.3.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.3.0_amd64.tar) | [:arrow_down: topohub_v0.3.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.3.0_amd64_checksum.sha512sum) | 2025-06-27 |
    | [v0.2.0](../../topohub/intro/release-notes.md) | AMD 64 | 47.89 MB | [:arrow_down: topohub_v0.2.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.2.0_amd64.tar) | [:arrow_down: topohub_v0.2.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.2.0_amd64_checksum.sha512sum) | 2025-06-17 |

## Verification

To verify the integrity of the downloaded offline package and checksum file,
run the following command in the directory:

```sh
# arch should be amd64 or arm64
# version should be vX.Y.Z
echo "$(cat topohub-dashboard_${version}_${arch}_checksum.sha512sum)" | sha512sum -c
```

Upon successful verification, the result will be similar to:

```none
topohub-dashboard_${version}_${arch}.tar: ok
```

## Installation

Refer to [offline upgrade of the device management module](../../topohub/intro/install.md) for installation.
If you have any license key-related questions, please contact the DaoCloud delivery team.
Email info@daocloud.io or call 400 002 6898.
