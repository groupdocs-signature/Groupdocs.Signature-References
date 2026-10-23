---
title: "Signaturen des bestimmten Typs löschen"
linkTitle: "Certain Type"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Dieser Artikel erklärt, wie man elektronische Signaturen des bestimmten Typs mit der GroupDocs.Signature API löscht."
type: docs
url: /de/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Bitte beachten Sie, dass die [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) Methode das gleiche Dokument modifiziert, das dem Konstruktor der [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) Klasse übergeben wurde, sodass das nachstehende Beispiel das signierte Dokument zuerst kopiert und die Signaturen aus der Kopie löscht.

## How to delete signatures of the certain type from the document
Hier sind die Schritte, um Signaturen des bestimmten Typs aus dem Dokument mit GroupDocs.Signature zu löschen:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

Dieses Beispiel zeigt, wie man alle Textsignaturen aus dem Dokument löscht. Nur die Signaturen, die GroupDocs.Signature hinzugefügt hat, werden gelöscht; der eigene Text des Dokuments bleibt unverändert.

{{< tabs "delete_signatures_by_type" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() speichert die Änderungen im geöffneten Dokument, daher arbeiten Sie mit einer Kopie
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Löschen Sie jede Textsignatur im Dokument
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab "signed.docx" >}}

`signed.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx), um sie herunterzuladen.

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

Sie können den obigen Code ganz einfach ausführen und die Funktion in Aktion in unseren GitHub‑Beispielen sehen:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Zusammen mit der voll ausgestatteten Python‑Bibliothek bieten wir einfache, aber leistungsstarke kostenlose Online‑Apps an.

Um PDF-, Word-, Excel-, PowerPoint- und andere Dokumente zu signieren, können Sie die Online‑Apps der **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** verwenden.
