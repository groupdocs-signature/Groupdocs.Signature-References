---
title: "TextSignOptions classe"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di firma Text."
type: docs
url: /it/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Rappresenta le opzioni di firma Text.

Maggiori informazioni

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

Il tipo TextSignOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Inizializza una nuova istanza della classe TextSignOptions con i valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Inizializza una nuova istanza della classe TextSignOptions con testo. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Le impostazioni dello sfondo della firma. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Le impostazioni del bordo. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Il carattere della firma. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Il colore di primo piano della firma. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Il titolo del campo modulo di testo in cui inserire la firma di testo. Può essere usato solo quando `signature_implementation` è impostato su `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Il tipo di campo modulo in cui inserire la firma testuale. Questa proprietà è applicabile solo quando `signature_implementation` è impostato su `TextSignatureImplementation.FORM_FIELD` (cioè, TextToFormField). Il valore predefinito è `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | L'altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri). L'unità è determinata dalla proprietà `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | L'allineamento orizzontale della firma nella pagina del documento. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | La posizione X sinistra della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri come definito dalla proprietà `MeasureType` LocationMeasureType). Funziona se l'allineamento orizzontale non è specificato. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà `left` e `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | Lo spazio tra la firma e i bordi del documento. Si applica solo quando è specificato l'allineamento orizzontale o verticale. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per il margine. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | L'attributo nativo. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | L'angolo di rotazione della firma nella pagina del documento (in senso orario). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | La posizione della forma definisce dove la forma dovrebbe essere presentata nel layout del documento. Disponibile solo per documenti Word. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Il tipo di forma per inserire il testo. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | L'ID univoco della firma, utilizzabile nelle opzioni di verifica e supportato solo per i documenti PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Il tipo di implementazione della firma testuale. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | La modalità di stretching sulla pagina del documento. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Il testo della firma. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | L'allineamento orizzontale del testo all'interno di una firma, supportato solo per le implementazioni di firma Image e Annotation (vedi la proprietà `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | L'allineamento verticale del testo all'interno di una firma. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | La posizione Y superiore della firma sulla pagina del documento, espressa in unità di misura (pixel, percentuale o millimetri). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | La trasparenza della firma, un valore float compreso tra 0.0 (opaco) e 1.0 (trasparente). Il valore predefinito è 0.0 (opaco). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | L'allineamento verticale della firma nella pagina del documento. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | La larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri; vedi la proprietà `MeasureType` `SizeMeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La firma verrà posizionata su tutte le pagine del documento. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | L'aspetto aggiuntivo della firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Il tipo di documento delle opzioni della firma (`DocumentType`). (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Le estensioni della firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | L'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Il numero di pagina del documento per la firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Le opzioni per specificare le pagine da firmare. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Il tipo di firma (`SignatureType`). (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La posizione Z-order della firma di testo, che determina l'ordine di visualizzazione delle firme sovrapposte. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Guide operative che utilizzano `TextSignOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
