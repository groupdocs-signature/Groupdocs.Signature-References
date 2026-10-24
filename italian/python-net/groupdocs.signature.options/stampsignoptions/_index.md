---
title: "Classe StampSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di firma Stamp."
type: docs
url: /it/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Rappresenta le opzioni di firma Stamp.

Per saperne di più:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

Il tipo StampSignOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Inizializza una nuova istanza della classe StampSignOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Inizializza una nuova istanza della classe StampSignOptions con opzioni di allineamento. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Cancella le risorse interne. (ereditato da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Crea una nuova istanza di ImageSignOptions con un'immagine predefinita da una stringa Base64. (ereditato da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | Lo sfondo del timbro. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | Il tipo di ritaglio del colore di sfondo della firma. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | Il tipo di ritaglio dell'immagine di sfondo della firma. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | L'altezza dell'area della firma sulla pagina del documento in unità di misura (pixel, percentuali o millimetri). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | L'allineamento orizzontale dell'immagine su una pagina del documento. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | L'elenco delle linee interne renderizzate come un insieme di rettangoli. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | La posizione X sinistra dell'area della firma sulla pagina del documento in unità di misura (pixel, percentuali o millimetri). Vedi `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà left e top. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | Lo spazio specificato per impostazione predefinita tra l'immagine e i bordi del documento (funziona se è specificato l'allineamento orizzontale o verticale). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | Il tipo di misura del margine (pixel, percentuali o millimetri). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | L'elenco delle linee esterne renderizzate come cerchi concentrici. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | L'angolo di rotazione in senso orario. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | Il tipo di timbro. Il valore predefinito è `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | La modalità di stretching nella pagina del documento. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | La posizione Y superiore dell'area della firma sulla pagina del documento in unità di misura (pixel, percentuali o millimetri). Vedi `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | La trasparenza della firma timbro. Il valore varia da 0,0 a 1,0, con un valore predefinito di 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | L'allineamento verticale del timbro su una pagina del documento. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | La larghezza dell'area della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri). L'unità di misura è definita da `MeasureType` SizeMeasureType. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La firma verrà posizionata su tutte le pagine del documento. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | L'aspetto aggiuntivo della firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Le impostazioni del bordo per la firma immagine. (eredita da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Il tipo di documento delle opzioni della firma (`DocumentType`). (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Le estensioni della firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | L'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Il percorso file dell'immagine della firma, usato solo se `image_stream` non è specificato. (eredita da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Il flusso dell'immagine della firma. Se specificato, viene sempre usato al posto di ImageFilePath. (eredita da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Il numero di pagina del documento per la firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Le opzioni per specificare le pagine da firmare. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Il rettangolo dell'area in cui posizionare l'immagine sul documento. (eredita da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | La posizione della forma definisce dove la forma dovrebbe essere presentata nel layout del documento. Disponibile solo per documenti Word. (eredita da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Il tipo di firma (`SignatureType`). (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La posizione Z-order della firma di testo, che determina l'ordine di visualizzazione delle firme sovrapposte. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # configura le opzioni aggiuntive del timbro secondo necessità
    signature.sign(options)
```

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
