---
title: "método delete"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Elimina el BaseSignature especificado del documento."
type: docs
url: /es/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Elimina la [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) especificada del documento.

Más información:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature | `BaseSignature` | Objeto BaseSignature que se eliminará del documento. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Ejemplo

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() guarda los cambios en el documento abierto, así que trabaje sobre una copia.
    shutil.copy("signed.docx", "text_signature_deleted.docx")
    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return
        if signature.delete(signatures[0]):
            print("Signature deleted")
```

## delete {#signatures}

Elimina la lista de firmas proporcionada del documento.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Lista de firmas a eliminar del documento. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Ejemplo

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Trabaje sobre una copia porque delete() guarda los cambios en el documento abierto.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Eliminar la primera firma encontrada.
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Elimina firmas del tipo especificado del documento.

Solo se eliminarán las firmas que fueron añadidas mediante el método `Sign` y marcadas como firmas ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)). Los tipos de firma compatibles son Texto, Imagen, Digital, Código de barras y Código QR.

```python
def delete(self, signature_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature_type | `SignatureType` | El tipo de firmas que se eliminarán del documento. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Lanza | Descripción |
| :- | :- |
| `Remarks` | - Más información: - Más sobre cómo eliminar firmas electrónicas de un documento en C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Casos de uso avanzados de eliminación de eFirmas de documentos: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Elimina firmas de la lista de `SignatureType` especificada del documento.

Solo se eliminarán las firmas que fueron añadidas mediante el método `Sign` y marcadas como firmas ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)). Los tipos de firma compatibles son Texto, Imagen, Digital, Código de barras y Código QR.

Aprende más
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | La lista de tipos de firma que se eliminarán del documento. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Elimina una firma por su Id de firma específico del documento.

Más información:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature_id | `str` | El Id de la firma que se eliminará del documento. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Elimina las firmas especificadas del documento.

Más información:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature_ids | `List[str]` | Lista de los identificadores de las firmas que se eliminarán del documento. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Ejemplo

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Trabaje sobre una copia porque delete() guarda los cambios en el documento abierto.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return

        text_signature = signatures[0]
        result = signature.delete([text_signature.id])
        if result.successful:
            print(f"Deleted text signature '{text_signature.text}'")
        else:
            print(f"Failed to delete text signature '{text_signature.text}'")
```

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
