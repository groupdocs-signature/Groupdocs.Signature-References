---
title: "快速入门指南"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "设置虚拟环境，安装 groupdocs-signature-net，并运行三个最小示例：使用文本签名对 PDF 进行签名，搜索签名，并验证它们。"
type: docs
url: /zh/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


本指南简要概述了如何设置并开始使用 GroupDocs.Signature for Python via .NET。该库只需几行代码即可在 PDF、Word、Excel、PowerPoint、OpenDocument 和图像文件中添加、查找、验证、更新和删除电子签名。

## Prerequisites

继续操作前，请确保您已拥有：

1. 如 [系统要求](https://docs.groupdocs.com/signature/python-net/system-requirements/) 章节所述的已配置环境。在 Linux 和 macOS 上，这包括一些系统软件包。
2. 可选地，获取一个用于测试所有产品功能的 [临时许可证](https://purchase.groupdocs.com/temporary-license/)。如果没有许可证，库将在评估模式下工作：它只能处理最多两页的文档，并在每个签名的页面添加评估行。参见 [授权](https://docs.groupdocs.com/signature/python-net/licensing/)。

## Set Up Your Development Environment

为了遵循最佳实践，请使用虚拟环境来管理依赖项。更多信息请参阅 [创建和使用虚拟环境](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) 指南。

### Create and Activate a Virtual Environment

创建虚拟环境：

{{< tabs \"create-venv\">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

激活它：

{{< tabs \"activate-venv\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs \"install-package\">}}
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

请参阅[Installation](/signature/python-net/guides/installation/)了解如何固定版本以及在无法访问 PyPI 时进行安装。

## Example 1: Sign a PDF with a Text Signature

打开文档，使用[TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/)描述签名，并保存已签名的副本。

{{< tabs \"sign_pdf_with_text_signature\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # 打开文档；with-block 在结束时会释放文件。
    with Signature("sample.pdf") as signature:
        # 文本签名位于第一页左边缘和上边缘各 100 像素处
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 签名并将结果保存到新文件；源文件保持不变
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例使用的示例文件。点击[here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf)下载。

{{< /tab >}}
{{< tab \"signed_sample.pdf\" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

查找文档已包含的签名。`search` 接受一个搜索选项列表，每种签名类型对应一个选项，并在 `result.signatures` 中返回它们。

{{< tabs \"search_document_for_signatures\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 在每页上查找文本签名
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` 是本示例使用的示例文件。点击[here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf)下载。

{{< /tab >}}
{{< tab \"search-document-signatures.txt\" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

检查文档是否包含您期望的签名。当找到完全匹配该文本的文本签名时，验证成功。

{{< tabs \"verify_text_signature\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` 是本示例使用的示例文件。点击[here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf)下载。

{{< /tab >}}
{{< tab \"verify-text-signature.txt\" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

将每个示例保存为与示例文件相邻的单独 `.py` 文件。您的文件夹应类似于如下所示：

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

运行该文件夹中的示例：

{{< tabs \"run-the-app\">}}
{{< tab \"Windows\" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

完成后，通过运行 `deactivate` 或关闭终端来停用虚拟环境。

## Apply a License

将 `GROUPDOCS_LIC_PATH` 环境变量设置为许可证文件的完整路径，导入 `groupdocs.signature` 时许可证会自动生效。无需编写代码。或者，也可以在代码中一次性设置，在任何其他调用之前：

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

[Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) 章节介绍了这两种方式以及计量许可证。

## Next Steps

完成基础学习后，探索其他资源：
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
