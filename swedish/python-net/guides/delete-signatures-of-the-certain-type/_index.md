---
title: "Ta bort signaturer av en viss typ"
linkTitle: "Certain Type"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Denna artikel förklarar hur man tar bort elektroniska signaturer av en viss typ med GroupDocs.Signature API."
type: docs
url: /sv/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Observera att metoden [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) ändrar samma dokument som skickades till konstruktorn för klassen [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature), så exemplet nedan kopierar först det signerade dokumentet och tar bort signaturerna från kopian.

## How to delete signatures of the certain type from the document
Här är stegen för att ta bort signaturer av en viss typ från dokumentet med GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

Detta exempel visar hur man tar bort alla textsignaturer från dokumentet. Endast de signaturer som GroupDocs.Signature har lagt till tas bort; dokumentets egen text förblir som den är.

{{< tabs \"delete_signatures_by_type\" >}}
{{< tab \"Python\" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() sparar ändringarna i det öppnade dokumentet, så arbeta på en kopia
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Ta bort varje textsignatur i dokumentet
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab \"signed.docx\" >}}

`signed.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) för att ladda ner den.

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

Du kan enkelt köra koden ovan och se funktionen i praktiken i våra GitHub-exempel:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tillsammans med det fullständiga Python-biblioteket erbjuder vi enkla men kraftfulla gratis online‑appar.

För att signera PDF, Word, Excel, PowerPoint och andra dokument kan du använda de online‑apparna från **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
