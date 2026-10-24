---
title: "ImageSignOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt de afbeeldingshandtekeningopties."
type: docs
url: /nl/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Vertegenwoordigt de afbeeldingshandtekeningopties.

Meer informatie:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

Het ImageSignOptions type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Initialiseert een nieuw exemplaar van de ImageSignOptions klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Initialiseert ImageSignOptions met een afbeeldingsbestand. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Initialiseert een nieuw ImageSignOptions exemplaar met een afbeeldingsstroom. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Wis interne bronnen. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Maakt een nieuw ImageSignOptions exemplaar met een vooraf gedefinieerde afbeelding uit een Base64‑string. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | De randinstellingen voor de afbeeldinghandtekening. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | De hoogte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters; zie `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | De horizontale uitlijning van de handtekening op de documentpagina. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Het bestandspad van de handtekeningafbeelding, alleen gebruikt als `image_stream` niet is gespecificeerd. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | De handtekeningafbeeldingsstroom. Indien gespecificeerd, wordt deze altijd gebruikt in plaats van ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | De linkse X-positie van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters). Werkt als de horizontale uitlijning niet is gespecificeerd. Zie `MeasureType` voor het locatie‑meettype. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de linker- en bovenste eigenschappen. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | De ruimte tussen de handtekening en de documentranden. Werkt alleen als horizontale of verticale uitlijning is gespecificeerd. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de marge. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | De rechthoek van het gebied om de afbeelding op het document te plaatsen. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | De rotatiehoek van de handtekening op de documentpagina (met de klok mee). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | De vormpositie bepaalt waar de vorm moet worden weergegeven in de documentlay-out. Alleen beschikbaar voor Word‑documenten. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | De uitrekmodus op de documentpagina. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | De bovenste Y‑positie van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters) zoals gedefinieerd door `MeasureType` LocationMeasureType. Werkt als de verticale uitlijning niet is gespecificeerd. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | De transparantie van de handtekening, variërend van 0,0 (ondoorzichtig) tot 1,0 (doorzichtig), standaard 0 (ondoorzichtig). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | De verticale uitlijning van de handtekening op de documentpagina. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | De breedte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters `MeasureType` grootte meettype). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | De handtekening wordt op alle documentpagina's geplaatst. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Het aanvullende handtekeninguiterlijk. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Het documenttype van de handtekeningopties (`DocumentType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | De handtekeningextensies. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Het hash‑algoritme dat moet worden gebruikt voor cryptografische bewerkingen. Exclusief ondersteund voor digitale handtekeningen in PDF‑bestanden. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Het paginanummer van het document voor ondertekening. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | De opties om pagina's op te geven die moeten worden ondertekend. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Het handtekeningtype (`SignatureType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | De Z‑orde positie van de tekshandtekening, die de weergavevolgorde van overlappende handtekeningen bepaalt. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Maak afbeeldingshandtekeningopties met het afbeeldingsbestand
        options = ImageSignOptions("signature.jpg")
        # Stel handtekeningpositie en -grootte in
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Taakgidsen die `ImageSignOptions` gebruiken:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
