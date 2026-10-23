---
title: "安装"
linkTitle: "Installation"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "从 PyPI 安装 GroupDocs.Signature for Python via .NET，将其固定在 requirements.txt 中，或在离线环境中安装预先下载的 wheel —— 然后验证安装是否成功。"
type: docs
url: /zh/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET 以自包含的 wheel 形式分发，内部捆绑了嵌入式 .NET 运行时。单个 `py3-none-{platform}` wheel 可在 Windows、Linux 和 macOS（Intel 与 Apple Silicon）上跨 Python **3.5 – 3.14** 使用。Windows 上无需其他依赖；Linux 和 macOS 需要以下列出的一些系统软件包。

在安装之前，请查看[系统要求](https://docs.groupdocs.com/signature/python-net/system-requirements/)。这些 wheel 需要 Linux 且 glibc 2.27 或更高，或 macOS 12 或更高，并且需要 pip 20.3 或更高才能安装。在 Linux 上，安装 ICU、fontconfig、`libgdiplus` 和 Microsoft 核心字体；在 macOS 上，安装 `mono-libgdiplus`。

## Install Package from PyPI

所有包都托管在[PyPI](https://pypi.org/project/groupdocs-signature-net/)。使用 `pip` 安装最新版本：

{{< tabs \"install-from-pypi\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

要将已有安装升级到最新发布，请添加 `--upgrade` 标志：

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

建议使用[虚拟环境](https://docs.python.org/3/library/venv.html)以使包及其依赖与系统 Python 隔离。请参阅[快速入门指南](/signature/python-net/guides/quick-start-guide/)了解 `venv` 设置步骤。

## Add the Package to `requirements.txt`

为了可重复构建，请在项目的 `requirements.txt` 中固定版本：

```text
groupdocs-signature-net==26.10.0
```

然后一次性安装所有依赖：

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

在无法访问 PyPI 的环境中（例如，隔离的 CI 运行器或受限服务器），请下载适用于您平台的 wheel 并从本地文件安装。

从[GroupDocs.Signature 发布页面](https://releases.groupdocs.com/signature/python-net/)下载与您的操作系统和 CPU 架构匹配的 wheel：

| 平台 | Wheel 文件名以以下结尾 | 最旧系统 |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27（Ubuntu 18.04，Debian 10，RHEL 8） |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

自 26.10 起，文件名标明了每个 wheel 可运行的最旧系统，因此 pip 20.3 或更高版本会在前期拒绝较旧的 wheel，而不是安装无法启动的运行时。至 26.1 版本的 wheel 使用标签 `manylinux1_x86_64`、`macosx_10_14_x86_64` 和 `macosx_11_0_arm64`，并包含 32 位 Windows wheel（`win32`）；现在已不再提供 32 位 wheel，请在 Windows 上使用 64 位 Python。

使用 `pip` 安装下载的文件（将文件名替换为您下载的 wheel）：

{{< tabs \"install-from-wheel\">}}
{{< tab \"Windows (64-bit)\" >}}
```ps
py -m pip install .\groupdocs_signature_net-26.10.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab \"Linux (glibc)\" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Apple Silicon)\" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< tab \"macOS (Intel)\" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

明确指定 wheel 文件名：PowerShell 不会为本机命令展开 `*` 通配符，因此 `pip install groupdocs_signature_net-*.whl` 在此会失败。

## Verify the Installation

确认已安装并可导入该包：

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

您也可以使用 `pip` 检查已安装的版本：

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
