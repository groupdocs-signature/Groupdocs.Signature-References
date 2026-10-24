---
title: "Удалить подписи определённого типа"
linkTitle: "Certain Type"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "В этой статье объясняется, как удалить электронные подписи определённого типа с помощью API GroupDocs.Signature."
type: docs
url: /ru/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Обратите внимание, что метод [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) изменяет тот же документ, который был передан в конструктор класса [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature), поэтому в примере ниже сначала копируется подписанный документ, а затем подписи удаляются из копии.

## How to delete signatures of the certain type from the document
Ниже перечислены шаги по удалению подписей определённого типа из документа с помощью GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

В этом примере показано, как удалить все текстовые подписи из документа. Удаляются только подписи, добавленные GroupDocs.Signature; собственный текст документа остаётся без изменений.

{{< tabs "delete_signatures_by_type" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() сохраняет изменения в открытом документе, поэтому работайте с копией
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Удалить каждую текстовую подпись в документе
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab "signed.docx" >}}

`signed.docx` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx), чтобы скачать его.

{{< /tab >}}
{{< tab "all_text_signatures_deleted.docx" >}}
```text
Binary file (DOCX, 147 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/delete_signatures_by_type/all_text_signatures_deleted.docx)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

Вы можете легко запустить приведённый выше код и увидеть работу функции в наших примерах на GitHub:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Вместе с полнофункциональной библиотекой Python мы предоставляем простые, но мощные бесплатные онлайн‑приложения.

Чтобы подписать PDF, Word, Excel, PowerPoint и другие документы, вы можете использовать онлайн‑приложения из **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
