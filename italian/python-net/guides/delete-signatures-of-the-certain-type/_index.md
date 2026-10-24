---
title: "Elimina le firme di un certo tipo"
linkTitle: "Certain Type"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Questo articolo spiega come eliminare le firme elettroniche di un certo tipo con l'API GroupDocs.Signature."
type: docs
url: /it/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Si prega di notare che il metodo [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) modifica lo stesso documento che è stato passato al costruttore della classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature), quindi l'esempio qui sotto copia prima il documento firmato ed elimina le firme dalla copia.

## How to delete signatures of the certain type from the document
Ecco i passaggi per eliminare le firme di un certo tipo dal documento con GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

Questo esempio mostra come eliminare tutte le firme testuali dal documento. Vengono eliminate solo le firme aggiunte da GroupDocs.Signature; il testo originale del documento rimane invariato.

{{< tabs \"delete_signatures_by_type\" >}}
{{< tab \"Python\" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() salva le modifiche nel documento aperto, quindi lavora su una copia.
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Elimina ogni firma testuale nel documento.
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab \"signed.docx\" >}}

`signed.docx` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) per scaricarlo.

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

Puoi facilmente eseguire il codice sopra e vedere la funzionalità in azione nei nostri esempi su GitHub:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Oltre alla libreria Python completa, forniamo semplici ma potenti app online gratuite.

Per firmare PDF, Word, Excel, PowerPoint e altri documenti puoi utilizzare le app online della **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
