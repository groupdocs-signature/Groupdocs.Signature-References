---
title: "DataMatrixEncodeMode 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "DataMatrixEncodeMode 枚举 — GroupDocs.Signature for Python via .NET API reference."
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

该 DataMatrixEncodeMode 类型公开以下成员：

### 字段
| 字段 | 描述 |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | 自动选择 DataMatrix 编码的最佳编码模式 |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | 每字节编码一个字母数字字符或两个数字字符 |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | 编码 8 位值 |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | 使用 BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding 中指定的编码进行编码 |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | 使用 C40 编码。编码大写字母数字、 小写字母和特殊字符 |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | 使用 Text 编码。编码小写字母数字、大写字母和特殊字符。 |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | 使用 EDIFACT 编码。每字符使用六位，编码数字、大写字母和多种标点符号，但不支持小写字母。 |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | 使用 ANSI X12 编码。 |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | ExtendedCodetext 模式允许在 code-text 中手动切换编码方案。格式："\Encodation_scheme_name:text\Encodation_scheme_name:text"。允许的编码方案有：EDIFACT、ANSIX12、ASCII、C40、Text、Auto。Extended code-text 示例：@"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" 文本中的所有反斜杠 (\) 必须加倍。 |

### 另见
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
