---
title: "classe Padding"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le informazioni di padding o margine associate all'elemento."
type: docs
url: /it/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Rappresenta le informazioni di padding o margine associate all'elemento.

Il tipo Padding espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Inizializza una nuova istanza della classe Padding con valori zero. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Inizializza una nuova istanza della classe Padding usando la dimensione di padding fornita per tutti i bordi. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Inizializza una nuova istanza della classe Padding usando le dimensioni di padding fornite. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Ottiene una copia di questo oggetto. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | Il valore di padding per tutti i bordi. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | Il valore di padding per il bordo inferiore. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | Il padding combinato per i bordi destro e sinistro. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | Il valore di padding per il bordo sinistro. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | Il valore di padding per il bordo destro. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | Il valore di padding per il bordo superiore. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | Il padding combinato per i bordi superiore e inferiore. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Fornisce un oggetto Padding senza alcun padding. |

### Esempio

```python
from groupdocs.signature.domain import Padding

# Padding uniforme di 5 unità su tutti i lati
uniform = Padding(5)

# Padding specifico a destra e in basso
custom = Padding(right=40, bottom=60)
```

### Guides
Guide delle attività che utilizzano `Padding`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
