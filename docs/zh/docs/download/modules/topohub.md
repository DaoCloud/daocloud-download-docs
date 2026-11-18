---
hide:
  - toc
---

# 设备管理

本页可下载设备管理各版本的离线安装包。

!!! tip

    `topohub` 是设备管理的内部开发代号。

## 下载

| 版本 | 架构 | 文件大小 | 安装包 | 校验文件 | 更新日期 |
| ---- | ---- | ----- | ----- | ------- | ------- |
| [v0.6.0](../../topohub/intro/release-notes.md) | AMD 64 | 51.91 MB | [:arrow_down: topohub-dashboard_v0.6.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.6.0_amd64.tar) | [:arrow_down: topohub-dashboard_v0.6.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.6.0_amd64_checksum.sha512sum) | 2025-12-26 |
| [v0.6.0](../../topohub/intro/release-notes.md) | <font color="green">ARM 64</font> | 49.36 MB | [:arrow_down: topohub-dashboard_v0.6.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.6.0_arm64.tar) | [:arrow_down: topohub-dashboard_v0.6.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.6.0_arm64_checksum.sha512sum) | 2025-12-26 |
| [v0.5.0](../../topohub/intro/release-notes.md) | AMD 64 | 51.90 MB | [:arrow_down: topohub-dashboard_v0.5.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.5.0_amd64.tar) | [:arrow_down: topohub-dashboard_v0.5.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.5.0_amd64_checksum.sha512sum) | 2025-10-29 |
| [v0.5.0](../../topohub/intro/release-notes.md) | <font color="green">ARM 64</font> | 49.34 MB | [:arrow_down: topohub-dashboard_v0.5.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.5.0_arm64.tar) | [:arrow_down: topohub-dashboard_v0.5.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.5.0_arm64_checksum.sha512sum) | 2025-10-29 |

??? note "展开查看历史版本"

    | 版本 | 架构 | 文件大小 | 安装包 | 校验文件 | 更新日期 |
    | ---- | ---- | ----- | ----- | ------- | ------- |
    | [v0.4.0](../../topohub/intro/release-notes.md) | AMD 64 | 52.47 MB | [:arrow_down: topohub-dashboard_v0.4.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.4.0_amd64.tar) | [:arrow_down: topohub-dashboard_v0.4.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.4.0_amd64_checksum.sha512sum) | 2025-08-29 |
    | [v0.4.0](../../topohub/intro/release-notes.md) | <font color="green">ARM 64</font> | 49.92 MB | [:arrow_down: topohub-dashboard_v0.4.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.4.0_arm64.tar) | [:arrow_down: topohub-dashboard_v0.4.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub-dashboard_v0.4.0_arm64_checksum.sha512sum) | 2025-08-29 |
    | [v0.3.0](../../topohub/intro/release-notes.md) | AMD 64 | 47.89 MB | [:arrow_down: topohub_v0.3.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.3.0_amd64.tar) | [:arrow_down: topohub_v0.3.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.3.0_amd64_checksum.sha512sum) | 2025-06-27 |
    | [v0.2.0](../../topohub/intro/release-notes.md) | AMD 64 | 47.89 MB | [:arrow_down: topohub_v0.2.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.2.0_amd64.tar) | [:arrow_down: topohub_v0.2.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.2.0_amd64_checksum.sha512sum) | 2025-06-17 |

## 校验

在下载离线安装包和校验文件的目录，执行以下命令校验完整性：

```sh
# arch 必须为 amd64 或 arm64
# version 版本号格式为：vX.Y.Z
echo "$(cat topohub-dashboard_${version}_${arch}_checksum.sha512sum)" | sha512sum -c
```

校验成功后打印结果类似于：

```none
topohub-dashboard_${version}_${arch}.tar: ok
```

## 安装

参阅[离线升级设备管理模块](../../topohub/intro/install.md)进行安装。
如果有任何许可密钥相关的问题，请联系 DaoCloud 交付团队。
电邮 info@daocloud.io 或致电 400 002 6898。
