---
title: "VerificationResult 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示保存验证过程结果的实例。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

表示保存验证过程结果的实例。

VerificationResult 类型公开以下成员：

### 属性
| 属性 | 描述 |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | 目标文档大小。对于验证，此变量始终为零。 |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | 验证过程中失败的签名列表。 |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | 验证结果；如果验证过程成功则为 True，否则为 False。 |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | 进程的执行时间（毫秒）。 |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | 源文档大小（字节）。 |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | 成功验证的签名列表 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。 |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | 已处理签名的总数。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
