---
title: "Clase Border"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa la apariencia del borde."
type: docs
url: /es/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Representa la apariencia del borde.

El tipo Border expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Implementa la interfaz IClonable. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | El color del borde de la firma. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | El estilo del borde de la firma. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | La transparencia del borde de la firma, que varía de 0.0 (opaco) a 1.0 (claro), por defecto 0 (opaco). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | La visibilidad del borde. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | El grosor del borde de la firma. |

### Ejemplo

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
Guías de tareas que usan `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
