---
title: "TextVerifyOptions classe"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Conserva le opzioni per verificare la firma Text del documento."
type: docs
url: /it/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

Conserva le opzioni per verificare la firma Text del documento.

Per saperne di più:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

Il tipo TextVerifyOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | Inizializza una nuova istanza di TextVerifyOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | Inizializza una nuova istanza di TextVerifyOptions con testo di verifica. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | Inizializza una nuova istanza di TextVerifyOptions con il testo da verificare e il tipo di implementazione della firma. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Il titolo del campo modulo da verificare. Se impostato, il testo verrà trovato solo nei campi modulo di testo. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Il tipo di campo modulo da verificare; se impostato, il testo verrà trovato solo nei campi modulo di testo. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | La verifica del tipo di corrispondenza del testo. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | L'ID della Text Signature da verificare. Deve essere maggiore di zero; supportato solo per documenti PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Il tipo di firma da verificare. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Il testo della firma da verificare. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Il flag indica se ogni pagina del documento deve essere verificata. Per impostazione predefinita il valore è True. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Le estensioni aggiuntive per la verifica delle opzioni di firma alternative. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Il flag della proprietà valida. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Il numero di pagina del documento da verificare; se non impostato, tutte le pagine del documento sono verificate per la prima occorrenza (valore minimo è 1). (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Le opzioni di pagina per specificare le pagine da verificare. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La posizione della forma nel layout del documento utilizzata per verificare le firme in intestazioni/piè di pagina. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
Guide operative che utilizzano `TextVerifyOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
