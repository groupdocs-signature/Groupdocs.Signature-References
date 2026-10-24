---
title: "Clase Padding"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa información de relleno o margen asociada al elemento."
type: docs
url: /es/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Representa información de relleno o margen asociada al elemento.

El tipo Padding expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Inicializa una nueva instancia de la clase Padding con valores cero. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Inicializa una nueva instancia de la clase Padding usando el tamaño de relleno suministrado para todos los bordes. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Inicializa una nueva instancia de la clase Padding usando los tamaños de relleno suministrados. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Obtiene una copia de este objeto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | El valor de relleno para todos los bordes. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | El valor de relleno para el borde inferior. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | El relleno combinado para los bordes derecho e izquierdo. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | El valor de relleno para el borde izquierdo. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | El valor de relleno para el borde derecho. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | El valor de relleno para el borde superior. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | El relleno combinado para los bordes superior e inferior. |

### Campos
| Campo | Descripción |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Proporciona un objeto Padding sin relleno. |

### Ejemplo

```python
from groupdocs.signature.domain import Padding

# Relleno uniforme de 5 unidades en todos los lados
uniform = Padding(5)

# Relleno específico a la derecha y abajo
custom = Padding(right=40, bottom=60)
```

### Guides
Guías de tareas que usan `Padding`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
