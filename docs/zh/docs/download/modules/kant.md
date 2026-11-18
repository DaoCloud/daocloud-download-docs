---
hide:
  - toc
---

# 云边协同

本页可下载云边协同各版本的离线安装包。

!!! tip

    `kant` 是云边协同的内部开发代号。

## 下载边端组件

这些边端组件离线包在接入边缘节点时使用。

- `keadm_init.sh`：用于初始化离线环境的 Shell 脚本，将离线包解压并将解压后的文件拷贝到指定工作目录
- `keadm_{arch}.tar.gz`：KubeEdge 安装工具 keadm 的压缩包
- `keadm_containerd_{arch}.tar.gz`：KubeEdge 安装工具 keadm 的压缩包，并且包含了默认版本的 containerd 安装包，可用于初始化默认容器运行时

| 安装包 | 架构 | 文件大小 | 校验文件 | 更新日期 |
| ----- | --- | ------- | ------- | ------ |
| [:arrow_down: keadm_init.sh](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_init.sh) | AMD 64 / <font color="green">ARM 64</font> | 2.31 KB | [:arrow_down: keadm_init_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_init_checksum.sha512sum) | 2025-12-26 |
| [:arrow_down: keadm_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_amd64.tar.gz) | AMD 64 | 31.40 MB | [:arrow_down: keadm_amd64.tar.gz_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_amd64.tar.gz_checksum.sha512sum) | 2025-12-26 |
| [:arrow_down: keadm_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_arm64.tar.gz) | <font color="green">ARM 64</font> | 55.78 MB | [:arrow_down: keadm_arm64.tar.gz_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_arm64.tar.gz_checksum.sha512sum) | 2025-12-26 |
| [:arrow_down: keadm_containerd_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_containerd_amd64.tar.gz) | AMD 64 | 158.69 MB | [:arrow_down: keadm_containerd_amd64.tar.gz_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_containerd_amd64.tar.gz_checksum.sha512sum) | 2025-12-26 |
| [:arrow_down: keadm_containerd_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_containerd_arm64.tar.gz) | <font color="green">ARM 64</font> | 163.86 MB | [:arrow_down: keadm_containerd_arm64.tar.gz_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/keadm_containerd_arm64.tar.gz_checksum.sha512sum) | 2025-12-26 |

## 下载云端组件

| 版本 | 架构 | 文件大小 | 安装包 | 校验文件 | 更新日期 |
| ----- | --- | --------- | -------- | -------- | --------- |
| [v0.22.0](../../kant/intro/release-notes.md) | AMD 64 | 177.30 MB | [:arrow_down: kant_v0.22.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.22.0_amd64.tar) | [:arrow_down: kant_v0.22.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.22.0_amd64_checksum.sha512sum) | 2025-12-26 |
| [v0.22.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 169.66 MB | [:arrow_down: kant_v0.22.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.22.0_arm64.tar) | [:arrow_down: kant_v0.22.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.22.0_arm64_checksum.sha512sum) | 2025-12-26 |
| [v0.21.0](../../kant/intro/release-notes.md) | AMD 64 | 171.45 MB | [:arrow_down: kant_v0.21.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.21.0_amd64.tar) | [:arrow_down: kant_v0.21.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.21.0_amd64_checksum.sha512sum) | 2025-09-25 |
| [v0.21.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 164.02 MB | [:arrow_down: kant_v0.21.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.21.0_arm64.tar) | [:arrow_down: kant_v0.21.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.21.0_arm64_checksum.sha512sum) | 2025-09-25 |
| [v0.20.0](../../kant/intro/release-notes.md) | AMD 64 | 168.19 MB | [:arrow_down: kant_v0.20.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.20.0_amd64.tar) | [:arrow_down: kant_v0.20.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.20.0_amd64_checksum.sha512sum) | 2025-06-23 |
| [v0.20.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 160.84 MB | [:arrow_down: kant_v0.20.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.20.0_arm64.tar) | [:arrow_down: kant_v0.20.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.20.0_arm64_checksum.sha512sum) | 2025-06-23 |

??? note "展开查看历史版本"

    | 版本 | 架构 | 文件大小 | 安装包 | 校验文件 | 更新日期 | 备注 |
    | ----- | --- | --------- | -------- | -------- | --------- | ----- |
    | [v0.19.1](../../kant/intro/release-notes.md) | AMD 64 | 107 MB | [:arrow_down: kant_v0.19.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.19.1_amd64.tar) | [:arrow_down: kant_v0.19.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.19.1_amd64_checksum.sha512sum) | 2025-03-31 | 云端 amd 安装包 |
    | [v0.19.1](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 103 MB | [:arrow_down: kant_v0.19.1_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.19.1_arm64.tar) | [:arrow_down: kant_v0.19.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.19.1_arm64_checksum.sha512sum) | 2025-03-31 | 云端 arm 安装包 |
    | [v0.19.1](../../kant/intro/release-notes.md) | AMD 64 | 15 MB | [:arrow_down: kantadm_v0.19.1_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.19.1_amd64.tar.gz) | [:arrow_down: kantadm_v0.19.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.19.1_amd64_checksum.sha512sum) | 2025-03-31 | 边端 amd 安装包 |
    | [v0.19.1](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 13 MB | [:arrow_down: kantadm_v0.19.1_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.19.1_arm64.tar.gz) | [:arrow_down: kantadm_v0.19.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.19.1_arm64_checksum.sha512sum) | 2025-03-31 | 边端 arm 安装包 |
    | [v0.18.0](../../kant/intro/release-notes.md) | AMD 64 | 107 MB | [:arrow_down: kant_v0.18.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.18.0_amd64.tar) | [:arrow_down: kant_v0.18.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.18.0_amd64_checksum.sha512sum) | 2024-12-30 | 云端 amd 安装包 |
    | [v0.18.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 103 MB | [:arrow_down: kant_v0.18.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.18.0_arm64.tar) | [:arrow_down: kant_v0.18.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.18.0_arm64_checksum.sha512sum) | 2024-12-30 | 云端 arm 安装包 |
    | [v0.18.0](../../kant/intro/release-notes.md) | AMD 64 | 15 MB | [:arrow_down: kantadm_v0.18.0_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_amd64.tar.gz) | [:arrow_down: kantadm_v0.18.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_amd64_checksum.sha512sum) | 2024-12-30 | 边端 amd 安装包 |
    | [v0.18.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 13 MB | [:arrow_down: kantadm_v0.18.0_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_arm64.tar.gz) | [:arrow_down: kantadm_v0.18.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_arm64_checksum.sha512sum) | 2024-12-30 | 边端 arm64 安装包 |
    | [v0.18.0](../../kant/intro/release-notes.md) | <font color="green">ARM 32</font> | 14 MB | [:arrow_down: kantadm_v0.18.0_arm.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_arm.tar.gz) | [:arrow_down: kantadm_v0.18.0_arm_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.18.0_arm_checksum.sha512sum) | 2024-12-30 | 边端 arm 安装包 |
    | [v0.17.0](../../kant/intro/release-notes.md) | AMD 64 | 107 MB | [:arrow_down: kant_v0.17.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.17.0_amd64.tar) | [:arrow_down: kant_v0.17.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.17.0_amd64_checksum.sha512sum) | 2024-11-28 | 云端 amd 安装包 |
    | [v0.17.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 103 MB | [:arrow_down: kant_v0.17.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.17.0_arm64.tar) | [:arrow_down: kant_v0.17.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.17.0_arm64_checksum.sha512sum) | 2024-11-28 | 云端 arm 安装包 |
    | [v0.17.0](../../kant/intro/release-notes.md) | AMD 64 | 15 MB | [:arrow_down: kantadm_v0.17.0_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_amd64.tar.gz) | [:arrow_down: kantadm_v0.17.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_amd64_checksum.sha512sum) | 2024-11-28 | 边端 amd 安装包 |
    | [v0.17.0](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 13 MB | [:arrow_down: kantadm_v0.17.0_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_arm64.tar.gz) | [:arrow_down: kantadm_v0.17.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_arm64_checksum.sha512sum) | 2024-11-28 | 边端 arm64 安装包 |
    | [v0.17.0](../../kant/intro/release-notes.md) | <font color="green">ARM 32</font> | 14 MB | [:arrow_down: kantadm_v0.17.0_arm.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_arm.tar.gz) | [:arrow_down: kantadm_v0.17.0_arm_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.17.0_arm_checksum.sha512sum) | 2024-11-28 | 边端 arm 安装包 |
    | [v0.16.1](../../kant/intro/release-notes.md) | AMD 64 | 107 MB | [:arrow_down: kant_v0.16.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.16.1_amd64.tar) | [:arrow_down: kant_v0.16.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.16.1_amd64_checksum.sha512sum) | 2024-11-04 | 云端 amd 安装包 |
    | [v0.16.1](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 103 MB | [:arrow_down: kant_v0.16.1_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.16.1_arm64.tar) | [:arrow_down: kant_v0.16.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kant_v0.16.1_arm64_checksum.sha512sum) | 2024-11-04 | 云端 arm 安装包 |
    | [v0.16.1](../../kant/intro/release-notes.md) | AMD 64 | 15 MB | [:arrow_down: kantadm_v0.16.1_amd64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_amd64.tar.gz) | [:arrow_down: kantadm_v0.16.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_amd64_checksum.sha512sum) | 2024-11-04 | 边端 amd 安装包 |
    | [v0.16.1](../../kant/intro/release-notes.md) | <font color="green">ARM 64</font> | 13 MB | [:arrow_down: kantadm_v0.16.1_arm64.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_arm64.tar.gz) | [:arrow_down: kantadm_v0.16.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_arm64_checksum.sha512sum) | 2024-11-04 | 边端 arm64 安装包 |
    | [v0.16.1](../../kant/intro/release-notes.md) | <font color="green">ARM 32</font> | 14 MB | [:arrow_down: kantadm_v0.16.1_arm.tar.gz](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_arm.tar.gz) | [:arrow_down: kantadm_v0.16.1_arm_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kantadm_v0.16.1_arm_checksum.sha512sum) | 2024-11-04 | 边端 arm 安装包 |

## 校验

在下载离线安装包和校验文件的目录，执行以下命令校验完整性：

```sh
echo "$(cat kant_0.6.1_amd64_checksum.sha512sum)" | sha512sum -c
```

校验成功后打印结果类似于：

```none
kant_0.6.1_amd64.tar: ok
```

## 安装

参阅[离线升级云边协同模块](../../kant/intro/offline-upgrade.md)进行安装。
如果有任何许可密钥相关的问题，请联系 DaoCloud 交付团队。
电邮 info@daocloud.io 或致电 400 002 6898。
