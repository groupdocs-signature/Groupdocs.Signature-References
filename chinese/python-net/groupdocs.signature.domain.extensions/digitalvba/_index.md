---
title: "DigitalVBA 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示用于 Spreadsheets VBA 项目的数字签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

表示用于 Spreadsheets VBA 项目的数字签名。

提供在电子表格文档格式（如 `Xlsm` 或 `Xltm`）中签署 VBA 项目的能力。如果将多个 [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) 扩展添加到 [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)，则在签署时仅使用第一个。

DigitalVBA 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | 使用证书文件初始化 DigitalVBA 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | 使用证书流初始化 DigitalVBA 类的新实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | 获取此对象的副本。（继承自 [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | 数字证书文件路径，仅在未指定 `CertificateStream` 时使用。 |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | 数字证书流。如果指定此属性，则始终使用它而不是 CertificateFilePath。 |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | 签名注释。 |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | 数字证书的密码。 |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | 决定是否仅签署 VBA 项目的设置。为 True 时，电子表格文档本身不被签署；仅签署 VBA 项目。 |

### 示例

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # 在电子表格中签署宏
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # 添加用于数字签署 VBA 项目的扩展
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # 验证已添加 VBA 项目签名部分
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### 另见
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
