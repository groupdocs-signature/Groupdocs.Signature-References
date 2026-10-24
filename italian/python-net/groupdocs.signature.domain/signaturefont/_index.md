---
title: "Classe SignatureFont"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "La classe SignatureFont specifica le proprietà del carattere per una firma di testo."
type: docs
url: /it/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

La classe SignatureFont specifica le proprietà del carattere per una firma di testo.

Il tipo SignatureFont espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Inizializza un SignatureFont con valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | Lo stile grassetto del carattere. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | Il nome della famiglia del carattere. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | Lo stile corsivo del carattere. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | La dimensione del carattere. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | Lo stile barrato del carattere. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | Lo stile sottolineato del carattere. |

### Esempio

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Guide operative che utilizzano `SignatureFont`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
