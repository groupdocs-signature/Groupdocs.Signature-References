---
title: "Eliminar firmas de un tipo determinado"
linkTitle: "Certain Type"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Este artículo explica cómo eliminar firmas electrónicas de un tipo determinado con la API de GroupDocs.Signature."
type: docs
url: /es/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Tenga en cuenta que el método [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) modifica el mismo documento que se pasó al constructor de la clase [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature), por lo que el ejemplo a continuación copia primero el documento firmado y elimina las firmas de la copia.

## How to delete signatures of the certain type from the document
A continuación se presentan los pasos para eliminar firmas de un tipo determinado del documento con GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

Este ejemplo muestra cómo eliminar todas las firmas de texto del documento. Solo se eliminan las firmas que GroupDocs.Signature añadió; el texto propio del documento permanece sin cambios.

{{< tabs "delete_signatures_by_type" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() guarda los cambios en el documento abierto, por lo que trabaje sobre una copia
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Eliminar todas las firmas de texto en el documento
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab "signed.docx" >}}

`signed.docx` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) para descargarlo.

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

Puede ejecutar fácilmente el código anterior y ver la función en acción en nuestros ejemplos de GitHub:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Junto con la biblioteca Python completa, ofrecemos aplicaciones en línea gratuitas, simples pero potentes.

Para firmar PDF, Word, Excel, PowerPoint y otros documentos, puedes usar las aplicaciones en línea de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
