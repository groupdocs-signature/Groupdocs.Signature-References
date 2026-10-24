---
title: "Classe QrCodeSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni della firma QR-Code."
type: docs
url: /it/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Rappresenta le opzioni della firma QR-Code.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

Il tipo QrCodeSignOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Inizializza una nuova istanza della classe QRCodeSignOptions con i valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Inizializza un'istanza di opzioni di firma QR code con il testo specificato. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Inizializza una nuova istanza della classe QrCodeSignOptions con il testo. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | L'allineamento del testo nell'immagine QR-code risultante, il valore predefinito è None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | L'oggetto personalizzato da serializzare nel contenuto QR-Code. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | L'implementazione di crittografia dei dati utilizzata per codificare e decodificare il testo o i dati della firma QR code. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | Il tipo di QR-Code. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | Il colore di primo piano delle barre del QR code; l'uso di questa proprietà potrebbe causare problemi di verifica, quindi usala con attenzione. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | L'altezza dell'area della firma sulla pagina del documento in unità di misura (pixel, percentuali o millimetri; vedere `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | L'allineamento orizzontale del QR code su una pagina del documento. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | Lo spazio tra gli elementi del QR code e i bordi dell'immagine risultante. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | La posizione X sinistra dell'area della firma su una pagina del documento in unità di misura (pixel, percentuali o millimetri). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà left e top. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | Il nome file dell'immagine del logo QR-code. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | Il flusso dell'immagine del logo QR-code. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | Lo spazio specificato per impostazione predefinita tra i bordi dell'Immagine e del Documento (funziona se è specificato l'allineamento orizzontale o verticale). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | Il tipo di misura del margine (pixel, percentuali o millimetri). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | Il flag per recuperare il contenuto dell'immagine QR-Code di una firma posizionata su una pagina del documento. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | Il tipo di file del contenuto immagine restituito della firma QR‑Code quando la proprietà `return_content` è abilitata. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | L'angolo di rotazione in gradi, in senso orario. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | La modalità di stretching nella pagina del documento. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | La posizione Y superiore dell'area della firma su una pagina del documento in unità di misura (pixel, percentuali o millimetri). L'unità è definita dalla proprietà `LocationMeasureType` di tipo `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | La trasparenza della firma QR code. Il valore varia da 0,0 a 1,0, con un valore predefinito di 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | L'allineamento verticale dell'immagine su una pagina del documento. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | La larghezza dell'area della firma sulla pagina del documento in valori di misura (pixel, percentuale o millimetri come definito da `MeasureType`). |
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
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Passa il testo e il tipo di QR code al costruttore
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Posiziona il QR code nell'angolo inferiore destro della pagina
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Colore del modulo, sfondo e un bordo puntinato con un po' di spazio interno
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
Guide operative che utilizzano `QrCodeSignOptions`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
