---
title: "DigitalSignOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt de digitale handtekeningopties."
type: docs
url: /nl/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Vertegenwoordigt de digitale handtekeningopties.

Meer informatie

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

Het DigitalSignOptions-type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Initialiseert een nieuw DigitalSignOptions-exemplaar met een certificaatbestand. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Initialiseert een nieuw DigitalSignOptions-exemplaar met een certificaatstroom. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met een certificaatbestand en een weergave‑afbeeldingsbestand. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Initialiseert een nieuw exemplaar van DigitalSignOptions met een certificaatbestand en een weergave‑afbeeldingsstroom. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Initialiseert een nieuw exemplaar van DigitalSignOptions met een certificaatstroom en een weergave‑afbeeldingsbestand. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Initialiseert een nieuw DigitalSignOptions-exemplaar met een certificaatstroom en een weergave‑afbeeldingsstroom. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Wis interne bronnen. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Maakt een nieuw ImageSignOptions-exemplaar met een vooraf gedefinieerde afbeelding uit een Base64‑string. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | De vlag die ondertekenen met een certificaat waarvan de geldigheidsperiode is verlopen toestaat. De standaardwaarde is False; ondertekenen met een verlopen certificaat veroorzaakt `GroupDocsSignatureException` en het document wordt niet ondertekend. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | De vlag die ondertekenen met een certificaat waarvan de geldigheidsperiode nog niet is begonnen toestaat. De standaardwaarde is False; ondertekenen met zo'n certificaat veroorzaakt `GroupDocsSignatureException` en het document wordt niet ondertekend. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Het bestandspad van het digitale certificaat. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | De digitale certificaatstroom. Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | Het ondertekeningscontact. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | De aangepaste hash‑ondertekeningsfunctie die wordt gebruikt om het document te ondertekenen, waardoor gebruikers hun eigen digitale ondertekeningslogica kunnen implementeren. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | De hoogte van het ondertekeningsgebied op de documentpagina in meeteenheden (pixels, procenten of millimeters; zie `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | De horizontale uitlijning van de afbeelding op een documentpagina. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | De linker X‑positie van het ondertekeningsgebied op de documentpagina in meeteenheden (pixels, procenten of millimeters zoals gedefinieerd door `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | De ondertekeningslocatie. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de left en top eigenschappen. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | De ruimte die standaard wordt gespecificeerd tussen de afbeelding en de documentranden (geldt wanneer horizontale of verticale uitlijning is opgegeven). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Het type marge‑meting (pixels, procenten of millimeters). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | Het wachtwoord van het digitale certificaat. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | De reden van de ondertekening. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | De rotatiehoek met de klok mee. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | De digitale ondertekenings‑eigenschappen voor het document. Voor PDF‑ondertekening kunnen geavanceerde eigenschappen worden ingesteld met een [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)‑instantie. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | De uitrekmodus op de documentpagina. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | De bovenste Y‑positie van het ondertekeningsgebied op de documentpagina in meeteenheden (pixels, procenten of millimeters; zie `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | De transparantie van de digitale ondertekening, variërend van 0.0 tot 1.0. Standaard is 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | De LTV (Long Term Validation) validatie‑vlag. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | De verticale uitlijning van de afbeelding op een documentpagina. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | De zichtbaarheid van de ondertekening. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | De breedte van het ondertekeningsgebied op de documentpagina in meetwaarden (pixels, procenten of millimeters). De meeteenheid wordt gedefinieerd door `MeasureType` via de SizeMeasureType‑eigenschap. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | Het XAdES‑type. Standaardwaarde is None (XAdES is uitgeschakeld). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | De handtekening wordt op alle documentpagina's geplaatst. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Het aanvullende handtekeninguiterlijk. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | De randinstellingen voor de afbeeldingondertekening. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Het documenttype van de handtekeningopties (`DocumentType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | De handtekeningextensies. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Het hash‑algoritme dat moet worden gebruikt voor cryptografische bewerkingen. Exclusief ondersteund voor digitale handtekeningen in PDF‑bestanden. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Het bestandspad van de ondertekeningsafbeelding, alleen gebruikt als `image_stream` niet is opgegeven. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | De ondertekenings‑afbeeldingsstroom. Indien opgegeven, wordt deze altijd gebruikt in plaats van ImageFilePath. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Het paginanummer van het document voor ondertekening. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | De opties om pagina's op te geven die moeten worden ondertekend. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | De rechthoek van het gebied om de afbeelding op het document te plaatsen. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | De vormpositie bepaalt waar de vorm moet worden weergegeven in de documentlay-out. Alleen beschikbaar voor Word‑documenten. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Het handtekeningtype (`SignatureType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | De Z‑orde positie van de tekshandtekening, die de weergavevolgorde van overlappende handtekeningen bepaalt. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Geef het certificaat en de weergave‑afbeelding door aan de constructor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Toon de ondertekening op de pagina, op deze positie en grootte
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Informatie opgeslagen in de handtekening
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Taakgidsen die `DigitalSignOptions` gebruiken:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
