---
title: "classe BarcodeSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni della firma barcode."
type: docs
url: /it/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Rappresenta le opzioni della firma barcode.

Maggiori informazioni

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

Il tipo BarcodeSignOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | Inizializza una nuova istanza della classe BarcodeSignOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | Inizializza una nuova istanza della classe BarcodeSignOptions con testo. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | Inizializza una nuova istanza della classe BarcodeSignOptions con testo. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | L'allineamento del testo nell'immagine barcode risultante. Il valore predefinito è None. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | Il tipo di barcode. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | Il colore di primo piano delle barre del barcode; usarlo può causare problemi di verifica, quindi usalo con cautela. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | L'altezza dell'area della firma nella pagina del documento in unità di misura (pixel, percentuali o millimetri). Vedi `MeasureType` per il tipo di misura della dimensione. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | L'allineamento orizzontale dell'immagine su una pagina del documento. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | Lo spazio tra gli elementi del barcode e i bordi dell'immagine risultante. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | La posizione X sinistra dell'area della firma nella pagina del documento, espressa in unità di misura (pixel, percentuali o millimetri). Vedi `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà left e top. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | Lo spazio specificato per impostazione predefinita tra l'immagine e i bordi del documento (applicabile quando è impostato l'allineamento orizzontale o verticale). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | Il tipo di misura del margine (pixel, percentuali o millimetri). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | Il flag che indica se recuperare il contenuto dell'immagine barcode di una firma posizionata su una pagina del documento. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | Il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà `return_content` è abilitata. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | L'angolo di rotazione in senso orario. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | La modalità di stretching nella pagina del documento. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | La posizione Y superiore dell'area della firma nella pagina del documento in unità di misura (pixel, percentuali o millimetri). Vedi `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | La trasparenza della firma barcode, che varia da 0,0 (completamente opaco) a 1,0 (completamente trasparente); il valore predefinito è 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | L'allineamento verticale dell'immagine barcode su una pagina del documento. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | La larghezza dell'area della firma nella pagina del documento in valori di misura (pixel, percentuali o millimetri) come definito da `MeasureType`. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La firma verrà posizionata su tutte le pagine del documento. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | L'aspetto aggiuntivo della firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Le impostazioni dello sfondo della firma. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Le impostazioni del bordo. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Il tipo di documento delle opzioni della firma (`DocumentType`). (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Le estensioni della firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Il carattere della firma. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Il titolo del campo modulo di testo in cui inserire la firma testuale. Può essere usato solo quando `signature_implementation` è impostato su `TextSignatureImplementation.FORM_FIELD`. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Il tipo di campo modulo in cui inserire la firma testuale. Questa proprietà è applicabile solo quando `signature_implementation` è impostato su `TextSignatureImplementation.FORM_FIELD` (cioè, TextToFormField). Il valore predefinito è `FormTextFieldType.ALL_TEXT_TYPES`. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | L'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | L'attributo nativo. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Il numero di pagina del documento per la firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Le opzioni per specificare le pagine da firmare. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | La posizione della forma definisce dove la forma dovrebbe essere presentata nel layout del documento. Disponibile solo per documenti Word. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Il tipo di forma per inserire il testo. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | L'ID univoco della firma, utilizzabile nelle opzioni di verifica e supportato solo per documenti PDF. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Il tipo di implementazione della firma di testo. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Il tipo di firma (`SignatureType`). (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Il testo della firma. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | L'allineamento orizzontale del testo all'interno di una firma, supportato solo per le implementazioni di firma Immagine e Annotazione (vedi la proprietà `TextSignatureImplementation` SignatureImplementation). (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | L'allineamento verticale del testo all'interno di una firma. (eredita da [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La posizione Z-order della firma di testo, che determina l'ordine di visualizzazione delle firme sovrapposte. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
Guide operative che utilizzano `BarcodeSignOptions`:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
