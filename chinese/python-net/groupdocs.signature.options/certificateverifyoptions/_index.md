---
title: "CertificateVerifyOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "保留验证证书文档的选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

保留验证证书文档的选项。

了解更多

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

该 CertificateVerifyOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | 使用默认值初始化 TextVerifyOptions 的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | 使用要验证的主题初始化一个新的 CertificateVerifyOptions 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | 该属性指示证书是否已过期，基于验证结果。 |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | 要验证的证书颁发者。 |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | 用于验证的文本匹配类型。 |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | 验证过程应使用基本验证策略提供 X.509 链验证。 |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | 要验证的证书序列号。 |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | 要验证的证书主题。 |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | 要验证的证书指纹。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 指示是否应验证每个文档页面的标志。默认值为 True。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 用于替代签名选项验证的额外扩展。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 有效属性标志。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 要验证的文档页码；如果未设置，则对文档的所有页面进行首次出现的验证（最小值为 1）。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 页面选项用于指定要验证的页面。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | 文档布局中用于在页眉/页脚中验证签名的形状位置。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
