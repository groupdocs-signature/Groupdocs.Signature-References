---
title: "Clase SignatureFont"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La clase SignatureFont especifica las propiedades de fuente para una firma de texto."
type: docs
url: /es/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

La clase SignatureFont especifica las propiedades de fuente para una firma de texto.

El tipo SignatureFont expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Inicializa un SignatureFont con valores predeterminados. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | El estilo negrita de la fuente. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | El nombre de la familia de la fuente. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | El estilo cursiva de la fuente. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | El tamaño de la fuente. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | El estilo tachado de la fuente. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | El estilo subrayado de la fuente. |

### Ejemplo

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Guías de tareas que usan `SignatureFont`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
