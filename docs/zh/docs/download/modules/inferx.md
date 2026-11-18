---
hide:
  - toc
---

# 推理加速

本页可下载推理加速模块各版本的离线安装包。

## 下载

| 版本 | 架构 | 文件大小 | 安装包 | 校验文件 | 更新日期 |
| ---- | --- | ------ | ------ | ------ | ------- |
| [v0.6.1](../../inferx/intro/release-notes.md) | AMD 64 | 21.49 GB | [:arrow_down: inferx_v0.6.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.6.1_amd64.tar) | [:arrow_down: inferx_v0.6.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.6.1_amd64_checksum.sha512sum) | 2026-10-29 |
| [v0.6.0](../../inferx/intro/release-notes.md) | AMD 64 | 21.48 GB | [:arrow_down: inferx_v0.6.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.6.0_amd64.tar) | [:arrow_down: inferx_v0.6.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.6.0_amd64_checksum.sha512sum) | 2026-10-19 |
| [v0.5.0](../../inferx/intro/release-notes.md) | AMD 64 | 22.27 GB | [:arrow_down: inferx_v0.5.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.5.0_amd64.tar) | [:arrow_down: inferx_v0.5.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.5.0_amd64_checksum.sha512sum) | 2026-09-03 |
| [v0.4.0](../../inferx/intro/release-notes.md) | AMD 64 | 9.90 GB | [:arrow_down: inferx_v0.4.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.4.0_amd64.tar) | [:arrow_down: inferx_v0.4.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.4.0_amd64_checksum.sha512sum) | 2026-07-20 |
| [v0.3.0](../../inferx/intro/release-notes.md) | AMD 64 | 10.77 GB | [:arrow_down: inferx_v0.3.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.3.0_amd64.tar) | [:arrow_down: inferx_v0.3.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.3.0_amd64_checksum.sha512sum) | 2026-06-08 |
| [v0.2.0](../../inferx/intro/release-notes.md) | AMD 64 | 10.77 GB | [:arrow_down: inferx_v0.2.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.2.0_amd64.tar) | [:arrow_down: inferx_v0.2.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.2.0_amd64_checksum.sha512sum) | 2026-05-12 |
| [v0.1.0](../../inferx/intro/release-notes.md) | AMD 64 | 9.98 GB | [:arrow_down: inferx_v0.1.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.1.0_amd64.tar) | [:arrow_down: inferx_v0.1.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/inferx_v0.1.0_amd64_checksum.sha512sum) | 2026-04-27 |

## 校验

在下载离线安装包和校验文件的目录，以 `v0.1.0_amd64` 为例，执行以下命令校验完整性：

```sh
echo "$(cat inferx_v0.1.0_amd64_checksum.sha512sum)" | sha512sum -c
```

校验成功后打印结果类似于：

```none
inferx_v0.1.0_amd64.tar: ok
```

## 安装

参阅推理加速离线安装步骤。
如果有任何许可密钥相关的问题，请联系 DaoCloud 交付团队。
电邮 info@daocloud.io 或致电 400 002 6898。
