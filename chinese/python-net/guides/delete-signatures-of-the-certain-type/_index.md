---
title: "删除特定类型的签名"
linkTitle: "Certain Type"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "本文介绍如何使用 GroupDocs.Signature API 删除特定类型的电子签名。"
type: docs
url: /zh/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
请注意，[delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) 方法会修改传入 [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) 类构造函数的同一文档，因此下面的示例会先复制已签名的文档，然后从副本中删除签名。

## How to delete signatures of the certain type from the document
以下是使用 GroupDocs.Signature 从文档中删除特定类型签名的步骤：

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

本示例展示了如何从文档中删除所有文本签名。仅会删除由 GroupDocs.Signature 添加的签名；文档原有的文本保持不变。

{{< tabs \"delete_signatures_by_type\" >}}
{{< tab \"Python\" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() 将更改保存到已打开的文档中，因此请在副本上操作
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # 删除文档中的所有文本签名
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab \"signed.docx\" >}}

`signed.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) 下载它。

{{< /tab >}}
{{< tab \"all_text_signatures_deleted.docx\" >}}
```text
Binary file (DOCX, 147 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/delete_signatures_by_type/all_text_signatures_deleted.docx)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

您可以轻松运行上述代码，并在我们的 GitHub 示例中看到该功能的实际效果：

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

除了功能齐全的 Python 库外，我们还提供简单但强大的免费在线应用程序。

要对 PDF、Word、Excel、PowerPoint 以及其他文档进行签名，您可以使用 **[GroupDocs.Signature 应用产品系列](https://products.groupdocs.app/signature/family)** 中的在线应用。
