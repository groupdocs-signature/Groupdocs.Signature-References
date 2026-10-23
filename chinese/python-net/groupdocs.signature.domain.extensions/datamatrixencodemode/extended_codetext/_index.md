---
title: "EXTENDED_CODETEXT 字段"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "ExtendedCodetext 模式允许手动切换 code-text 中的编码方案。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

ExtendedCodetext 模式允许在 code-text 中手动切换编码方案。格式："\Encodation_scheme_name:text\Encodation_scheme_name:text"。允许的编码方案有：EDIFACT、ANSIX12、ASCII、C40、Text、Auto。Extended code-text 示例：@"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" 文本中的所有反斜杠 (\) 必须加倍。

### 值
`12`

### 另见
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
