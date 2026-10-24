---
title: "Classe ImageSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni della firma immagine."
type: docs
url: /it/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Rappresenta le opzioni della firma immagine.

Per saperne di più:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

Il tipo ImageSignOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Inizializza una nuova istanza della classe ImageSignOptions con i valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Inizializza ImageSignOptions con un file immagine. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Inizializza una nuova istanza di ImageSignOptions con un flusso di immagine. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Cancella le risorse interne. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Crea una nuova istanza di ImageSignOptions con un'immagine predefinita da una stringa Base64. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Le impostazioni del bordo per la firma immagine. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | L'altezza della firma nella pagina del documento in valori di misura (pixel, percentuali o millimetri; vedere `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | L'allineamento orizzontale della firma nella pagina del documento. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Il percorso file dell'immagine della firma, usato solo se `image_stream` non è specificato. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Il flusso dell'immagine della firma. Se specificato, viene sempre usato al posto di ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | La posizione X sinistra della firma nella pagina del documento in valori di misura (pixel, percentuali o millimetri). Funziona se l'allineamento orizzontale non è specificato. Vedere `MeasureType` per il tipo di misura della posizione. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà left e top. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | Lo spazio tra la firma e i bordi del documento. Funziona solo se sono specificati l'allineamento orizzontale o verticale. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per il margine. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Il rettangolo dell'area in cui inserire l'immagine nel documento. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | L'angolo di rotazione della firma nella pagina del documento (in senso orario). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | La posizione della forma definisce dove la forma dovrebbe essere presentata nel layout del documento. Disponibile solo per documenti Word. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | La modalità di stretching nella pagina del documento. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | La posizione Y superiore della firma nella pagina del documento in valori di misura (pixel, percentuali o millimetri) come definito da `MeasureType` LocationMeasureType. Funziona se l'allineamento verticale non è specificato. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | La trasparenza della firma, che varia da 0,0 (opaca) a 1,0 (trasparente), il valore predefinito è 0 (opaca). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | L'allineamento verticale della firma nella pagina del documento. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | La larghezza della firma nella pagina del documento in valori di misura (pixel, percentuali o millimetri `MeasureType` tipo di misura della dimensione). |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Crea opzioni di firma immagine con il file immagine
        options = ImageSignOptions("signature.jpg")
        # Imposta la posizione e le dimensioni della firma
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Guide operative che utilizzano `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
