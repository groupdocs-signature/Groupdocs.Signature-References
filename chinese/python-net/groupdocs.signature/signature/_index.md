---
title: "Signature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示控制文档签名过程的主类。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

表示控制文档签名过程的主类。

了解更多关于 GroupDocs.Signature 功能的信息：
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Signature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | 使用作为流提供的文档初始化新的 Signature 实例。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | 使用文档流和加载选项初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | 使用通过流提供的文档和可选的 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) 初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | 使用文档流、加载选项和签名设置初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | 使用文件路径提供的文档初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | 使用文件路径提供的文档和加载选项初始化新的 Signature 实例。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | 使用文件路径提供的文档和可选的 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) 初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | 使用文件路径提供的文档、加载选项和签名设置初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | 从文档中删除指定的 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | 从文档中删除提供的签名列表。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | 从文档中删除指定类型的签名。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | 从文档中删除指定 `SignatureType` 列表的签名。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | 从文档中根据特定的签名 Id 删除签名。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | 从文档中删除指定的签名。 |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | 清理签名对象使用的内部资源。 |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | 生成文档页面预览。 |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | 根据给定的 SignOptions 生成签名预览。 |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | 获取文档页面信息：它们的尺寸、最大页面高度以及具有最大高度的页面的宽度。 |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | 使用一组 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) 在文档中搜索签名。 |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | 使用提供的搜索选项在文档中搜索签名，并根据指定的谓词过滤结果。 |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | 通过 `SignatureType` 值在文档中搜索指定的签名类型。 |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | 使用所有可用的搜索选项在文档中搜索签名，并根据指定的谓词过滤结果。 |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | 使用 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并将结果保存到流中。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | 使用 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并使用预定义的 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) 将结果保存到流中。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | 使用一组 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并将结果保存到流中。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | 使用一组 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并使用预定义的 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) 将结果保存到流中。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | 使用 SignOptions 对文档进行签名，并将结果保存到指定的文件路径。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | 使用 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并使用预定义的 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) 将结果保存到指定的文件路径。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | 使用 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 集合对文档进行签名，并将结果保存到指定的文件路径。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | 使用一组 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并使用预定义的 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) 将结果保存到指定的文件路径。 |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | 更新文档中传入的签名 BaseSignature。 |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | 更新文档中传入的签名 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。 |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | 使用给定的 VerifyOptions 数据验证文档签名。 |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | 使用提供的验证选项验证文档签名，并根据指定的谓词过滤结果。 |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | 使用 VerifyOptions 数据列表验证文档签名。 |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | 使用提供的验证选项验证文档签名，并使用给定的谓词过滤结果。 |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
使用 `Signature` 的任务指南：

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### 另见
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
