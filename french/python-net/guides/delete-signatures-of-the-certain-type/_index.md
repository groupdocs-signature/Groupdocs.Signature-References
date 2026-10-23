---
title: "Supprimer les signatures d'un certain type"
linkTitle: "Certain Type"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Cet article explique comment supprimer les signatures électroniques d'un certain type avec l'API GroupDocs.Signature."
type: docs
url: /fr/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Veuillez noter que la méthode [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) modifie le même document qui a été passé au constructeur de la classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature), donc l'exemple ci‑dessous copie d'abord le document signé et supprime les signatures de la copie.

## How to delete signatures of the certain type from the document
Voici les étapes pour supprimer les signatures d'un certain type du document avec GroupDocs.Signature :

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

Cet exemple montre comment supprimer toutes les signatures texte du document. Seules les signatures ajoutées par GroupDocs.Signature sont supprimées ; le texte propre du document reste tel quel.

{{< tabs "delete_signatures_by_type" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() enregistre les modifications dans le document ouvert, donc travaillez sur une copie
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Supprimer chaque signature texte du document
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab "signed.docx" >}}

`signed.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) pour le télécharger.

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

Vous pouvez facilement exécuter le code ci‑dessus et voir la fonctionnalité en action dans nos exemples GitHub :

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

En plus de la bibliothèque Python complète, nous proposons des applications en ligne simples mais puissantes et gratuites.

Pour signer des PDF, Word, Excel, PowerPoint et d'autres documents, vous pouvez utiliser les applications en ligne de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
