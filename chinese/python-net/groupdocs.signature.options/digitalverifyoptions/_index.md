---
title: "DigitalVerifyOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "保留验证文档数字签名的选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

保留验证文档数字签名的选项。

了解更多

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

DigitalVerifyOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | 使用默认值初始化 DigitalVerifyOptions 实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | 使用给定的数字证书文件路径初始化 DigitalVerifyOptions 实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | 使用给定的证书流初始化 DigitalVerifyOptions 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | 从证书文件路径或流获取的 X509Certificate2 证书。 |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | 数字证书的文件路径。 |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | 数字证书的流。 |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | 要验证的数字签名的注释。 |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | 要验证的签名联系人。 |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | 要验证的证书的颁发者名称。 |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | 要验证的签名位置。 |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | 如果需要，数字证书的密码。 |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | 要验证的数字签名原因。 |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | 要验证的数字签名的日期时间范围的开始。None 值将被忽略。 |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | 要验证的数字签名的日期时间范围的结束。null 值将被忽略。 |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | 要验证的证书的主题可辨识名称；验证会检查签名的主题名称是否包含或等于此区分大小写的值。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 指示是否应验证每个文档页面的标志。默认值为 True。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 用于替代签名选项验证的额外扩展。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 有效属性标志。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 要验证的文档页码；如果未设置，则对文档的所有页面进行首次出现的验证（最小值为 1）。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 页面选项用于指定要验证的页面。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | 文档布局中用于在页眉/页脚中验证签名的形状位置。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
