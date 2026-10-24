---
title: "Handtekeningen van een bepaald type verwijderen"
linkTitle: "Certain Type"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Dit artikel legt uit hoe u elektronische handtekeningen van een bepaald type kunt verwijderen met de GroupDocs.Signature API."
type: docs
url: /nl/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Houd er rekening mee dat de [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete)‑methode hetzelfde document wijzigt dat aan de constructor van de [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature)‑klasse is doorgegeven, dus het onderstaande voorbeeld kopieert eerst het ondertekende document en verwijdert de handtekeningen uit de kopie.

## How to delete signatures of the certain type from the document
Hier zijn de stappen om handtekeningen van een bepaald type uit het document te verwijderen met GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

Dit voorbeeld toont hoe alle tekstehandsignatures uit het document te verwijderen. Alleen de handtekeningen die GroupDocs.Signature heeft toegevoegd, worden verwijderd; de eigen tekst van het document blijft ongewijzigd.

{{< tabs "delete_signatures_by_type" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() slaat de wijzigingen op in het geopende document, werk dus op een kopie
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Verwijder elke tekstehandsignature in het document
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab "signed.docx" >}}

`signed.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) om het te downloaden.

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

U kunt de bovenstaande code eenvoudig uitvoeren en de functie in actie zien in onze GitHub-voorbeelden:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Naast de volledig uitgeruste Python-bibliotheek bieden we eenvoudige maar krachtige gratis online apps.

Om PDF, Word, Excel, PowerPoint en andere documenten te ondertekenen, kun je de online apps van de **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** gebruiken.
