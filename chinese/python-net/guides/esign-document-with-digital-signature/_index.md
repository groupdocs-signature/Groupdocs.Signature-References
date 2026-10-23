---
title: "使用数字签名签署文档"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "了解使用数字签名安全签署文档的好处。学习如何在 Python 中通过分步指南以编程方式添加数字签名。"
type: docs
url: /zh/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

在当今数字时代，确保电子文档的真实性和完整性至关重要。实现这一目标的高效方法之一是使用数字签名。在本指南中，我们将探讨数字签名的概念，说明它们是什么、为何必不可少，以及如何利用 GroupDocs.Signature for Python via .NET 无缝地对文档进行电子签名。

## What is a Digital Signature?

数字签名是一种用于验证电子文档真实性和完整性的加密机制。它能够强有力地保证文档来源于已知发送者且未被未经授权的来源篡改。数字签名通常由包含私钥（用于签名）和公钥（用于验证）的证书表示。各种公钥密码学标准，如 PFX 格式，常用于此目的。
下图展示了默认情况下数字签名在 PDF 文档页面上的显示效果。

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

已过期或尚未生效的证书会被拒绝：`sign` 抛出 [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) 并显示类似 "The signing certificate expired on ..." 的信息。若仍要使用此类证书进行签名，请将 `allow_expired` 或 `allow_not_yet_valid` 设置为 `True`。

### Follow these steps to sign your documents with a digital signature

1. 使用 pip 安装 GroupDocs.Signature 包：
```bash
pip install groupdocs-signature-net
```

2. 创建 [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) 类的新实例，并将源文档路径作为构造函数参数传入。
3. 实例化 [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) 对象，并提供所需的证书及其密码。
4. 调用 [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) 方法的 [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) 类实例，并将 [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) 传递给它。

下面的示例展示了如何使用 Python 对 PDF 文档进行数字电子签名。我们可以以相同的方式签署任何其他受支持的文档格式。

{{< tabs \"sign_with_digital_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # 使用证书文件创建数字签名选项
        options = DigitalSignOptions("certificate.pfx")

        # 设置证书密码
        options.password = "1234567890"

        # 可选：显示页面上签名的图像
        options.image_file_path = "signature.jpg"

        # 设置签名位置
        options.left = 100
        options.top = 400

        # 对文档进行签名并保存结果
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例使用的示例文件。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) 下载它。

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` 是本示例使用的示例证书（密码 `1234567890`）。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) 下载它。

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` 是本示例使用的示例文件。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) 下载它。

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

您可以通过额外选项进一步自定义数字签名：签名在页面上的大小，以及存储在其中的联系人、原因和位置：

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 将证书和外观图像传递给构造函数
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # 在页面上显示签名，位于此位置并具有此大小
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # 签名中存储的信息
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例使用的示例文件。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) 下载它。

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` 是本示例使用的示例证书（密码 `1234567890`）。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) 下载它。

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` 是本示例使用的示例文件。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) 下载它。

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

您也可以从流中加载证书。保持流打开，直至 `sign` 返回：

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # 从流中加载证书
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # 设置签名的位置和大小
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例使用的示例文件。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) 下载它。

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` 是本示例使用的示例证书（密码 `1234567890`）。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) 下载它。

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
本指南演示了如何使用 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) 对文档进行数字签名。它解释了如何加载文档、配置基于证书的签名以及安全地保存已签名文件。还涵盖了高级功能，例如签名外观和签名中存储的信息。请参阅相关资源以获取有关数字签名工作流的更多详细信息。

## More Resources

### GitHub Examples

您可以轻松运行上述代码，并在我们的 GitHub 示例中看到该功能的实际效果：

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

除了功能齐全的 Python 库外，我们还提供简单但强大的免费在线应用程序。

要对 PDF、Word、Excel、PowerPoint 以及其他文档进行签名，您可以使用 **[GroupDocs.Signature 应用产品系列](https://products.groupdocs.app/signature/family)** 中的在线应用。
