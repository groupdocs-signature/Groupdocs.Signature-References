---
title: "Classe DigitalSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni della firma digitale."
type: docs
url: /it/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Rappresenta le opzioni della firma digitale.

Maggiori informazioni

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

Il tipo DigitalSignOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Inizializza una nuova istanza della classe DigitalSignOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Inizializza una nuova istanza di DigitalSignOptions con un file di certificato. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Inizializza una nuova istanza di DigitalSignOptions con un flusso di certificato. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Inizializza una nuova istanza della classe DigitalSignOptions con un file di certificato e un file immagine di aspetto. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Inizializza una nuova istanza di DigitalSignOptions con un file di certificato e un flusso immagine di aspetto. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Inizializza una nuova istanza di DigitalSignOptions con un flusso di certificato e un file immagine di aspetto. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Inizializza una nuova istanza di DigitalSignOptions con un flusso di certificato e un flusso immagine di aspetto. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Cancella le risorse interne. (ereditato da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Crea una nuova istanza di ImageSignOptions con un'immagine predefinita da una stringa Base64. (ereditato da [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | Il flag che consente la firma con un certificato il cui periodo di validità è terminato. Il valore predefinito è False; firmare con un certificato scaduto genera `GroupDocsSignatureException` e il documento non viene firmato. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | Il flag che consente la firma con un certificato il cui periodo di validità non è ancora iniziato. Il valore predefinito è False; firmare con tale certificato genera `GroupDocsSignatureException` e il documento non viene firmato. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Il percorso del file del certificato digitale. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | Il flusso del certificato digitale. Se questa proprietà è specificata, viene sempre usata al posto di CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | Il contatto della firma. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | La funzione di firma hash personalizzata utilizzata per firmare il documento, consentendo agli utenti di implementare la propria logica di firma digitale. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | L'altezza dell'area della firma sulla pagina del documento in unità di misura (pixel, percentuali o millimetri; vedere `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | L'allineamento orizzontale dell'immagine su una pagina del documento. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | La posizione X sinistra dell'area della firma sulla pagina del documento in unità di misura (pixel, percentuali o millimetri come definito da `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | La posizione della firma. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà left e top. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | Lo spazio specificato per impostazione predefinita tra l'immagine e i bordi del documento (vale quando è specificato l'allineamento orizzontale o verticale). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Il tipo di misura del margine (pixel, percentuali o millimetri). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | La password del certificato digitale. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | Il motivo della firma. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | L'angolo di rotazione in senso orario. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | Le proprietà della firma digitale per il documento. Per la firma PDF, è possibile impostare proprietà avanzate utilizzando un'istanza di [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/). |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Il tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | La modalità di stretching nella pagina del documento. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | La posizione Y superiore dell'area della firma sulla pagina del documento in unità di misura (pixel, percentuali o millimetri; vedere `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | La trasparenza della firma digitale, compresa tra 0.0 e 1.0. Il valore predefinito è 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | Il flag di convalida LTV (Long Term Validation). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | L'allineamento verticale dell'immagine su una pagina del documento. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | La visibilità della firma. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | La larghezza dell'area della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri). L'unità di misura è definita da `MeasureType` tramite la proprietà SizeMeasureType. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | Il tipo XAdES. Il valore predefinito è None (XAdES è disattivato). |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Passa il certificato e l'immagine di aspetto al costruttore
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Mostra la firma sulla pagina, in questa posizione e dimensione
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Informazioni memorizzate nella firma
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Guide operative che utilizzano `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
