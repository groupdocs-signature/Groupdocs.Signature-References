---
title: "Padding klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt opvul- of marge-informatie die aan een element is gekoppeld voor."
type: docs
url: /nl/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Stelt opvul- of marge-informatie die aan een element is gekoppeld voor.

Het Padding-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Initialiseert een nieuw exemplaar van de Padding-klasse met nulwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Initialiseert een nieuw exemplaar van de Padding-klasse met de opgegeven opvulgrootte voor alle randen. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Initialiseert een nieuw exemplaar van de Padding-klasse met de opgegeven opvulgroottes. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Haalt een kopie van dit object op. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | De opvulwaarde voor alle randen. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | De opvulwaarde voor de onderrand. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | De gecombineerde opvulling voor de rechter- en linker randen. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | De opvulwaarde voor de linkerrand. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | De opvulwaarde voor de rechterrand. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | De opvulwaarde voor de bovenrand. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | De gecombineerde opvulling voor de boven- en onderranden. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Biedt een Padding-object zonder opvulling. |

### Voorbeeld

```python
from groupdocs.signature.domain import Padding

# Gelijke opvulling van 5 eenheden aan alle zijden
uniform = Padding(5)

# Specifieke opvulling aan de rechter- en onderkant
custom = Padding(right=40, bottom=60)
```

### Guides
Taakgidsen die `Padding` gebruiken:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
