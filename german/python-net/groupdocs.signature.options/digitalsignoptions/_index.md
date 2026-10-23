---
title: "Klasse DigitalSignOptions"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die digitalen Signaturoptionen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Stellt die digitalen Signaturoptionen dar.

Mehr erfahren

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

Der Typ DigitalSignOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Initialisiert eine neue DigitalSignOptions-Instanz mit einer Zertifikatsdatei. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Initialisiert eine neue DigitalSignOptions-Instanz mit einem Zertifikats-Stream. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einer Erscheinungsbild-Bilddatei. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Initialisiert eine neue Instanz von DigitalSignOptions mit einer Zertifikatsdatei und einem Erscheinungsbild-Image-Stream. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Initialisiert eine neue Instanz von DigitalSignOptions mit einem Zertifikats-Stream und einer Erscheinungsbild-Bilddatei. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Initialisiert eine neue DigitalSignOptions-Instanz mit einem Zertifikats-Stream und einem Erscheinungsbild-Image-Stream. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Löscht interne Ressourcen. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Erstellt eine neue ImageSignOptions-Instanz mit einem vordefinierten Bild aus einem Base64-String. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | Das Flag, das das Signieren mit einem Zertifikat ermöglicht, dessen Gültigkeitszeitraum abgelaufen ist. Der Standardwert ist False; das Signieren mit einem abgelaufenen Zertifikat löst `GroupDocsSignatureException` aus und das Dokument wird nicht signiert. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | Das Flag, das das Signieren mit einem Zertifikat ermöglicht, dessen Gültigkeitszeitraum noch nicht begonnen hat. Der Standardwert ist False; das Signieren mit einem solchen Zertifikat löst `GroupDocsSignatureException` aus und das Dokument wird nicht signiert. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Der Dateipfad des digitalen Zertifikats. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | Der digitale Zertifikat-Stream. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von CertificateFilePath verwendet. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | Der Signaturkontakt. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | Die benutzerdefinierte Hash‑Signaturfunktion, die zum Signieren des Dokuments verwendet wird und es Benutzern ermöglicht, ihre eigene digitale Signaturlogik zu implementieren. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | Die Höhe des Signaturbereichs auf der Dokumentseite in Maßeinheiten (Pixel, Prozente oder Millimeter; siehe `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | Die horizontale Ausrichtung des Bildes auf einer Dokumentseite. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | Die linke X‑Position des Signaturbereichs auf der Dokumentseite in Maßeinheiten (Pixel, Prozente oder Millimeter, wie durch `MeasureType.location_measure_type` definiert). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | Der Signaturort. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Der Maßtyp (Pixel, Prozente oder Millimeter) für die linken und oberen Eigenschaften. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | Der standardmäßig angegebene Abstand zwischen Bild und Dokumenträndern (gilt, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Der Messungstyp für den Rand (Pixel, Prozente oder Millimeter). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | Das Passwort des digitalen Zertifikats. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | Der Grund der Signatur. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | Der Rotationswinkel im Uhrzeigersinn. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | Die digitalen Signatur‑Eigenschaften für das Dokument. Für das PDF‑Signieren können erweiterte Eigenschaften mit einer [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)‑Instanz festgelegt werden. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Der Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | Der Dehnungsmodus auf der Dokumentenseite. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | Die obere Y‑Position des Signaturbereichs auf der Dokumentseite in Maßeinheiten (Pixel, Prozente oder Millimeter; siehe `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | Die Transparenz der digitalen Signatur, im Bereich von 0,0 bis 1,0. Standard ist 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | Das LTV‑(Long Term Validation) Validierungs‑Flag. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | Die vertikale Ausrichtung des Bildes auf einer Dokumentseite. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | Die Sichtbarkeit der Signatur. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | Die Breite des Signaturbereichs auf der Dokumentseite in Messwerten (Pixel, Prozente oder Millimeter). Die Maßeinheit wird durch `MeasureType` über die Eigenschaft SizeMeasureType definiert. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | Der XAdES‑Typ. Der Standardwert ist None (XAdES ist deaktiviert). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Die Signatur wird auf allen Dokumentenseiten platziert. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Das zusätzliche Signatur‑Aussehen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Die Rahmen‑Einstellungen für die Bildsignatur. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Der Dokumenttyp der Signaturoptionen (`DocumentType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Die Signatur‑Erweiterungen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Der Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird. Unterstützt ausschließlich für digitale Signaturen in PDF‑Dateien. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Der Dateipfad des Signatur‑Bildes, der nur verwendet wird, wenn `image_stream` nicht angegeben ist. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Der Signatur‑Bild‑Stream. Wenn angegeben, wird er stets anstelle von ImageFilePath verwendet. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Die Dokumentenseitenzahl zum Signieren. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Die Optionen, um die zu signierenden Seiten anzugeben. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Das Rechteck des Bereichs, in dem das Bild im Dokument platziert wird. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Die Position der Form definiert, wo die Form im Dokumentlayout dargestellt werden soll. Nur für Word-Dokumente verfügbar. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Der Signaturtyp (`SignatureType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Die Z‑Reihenfolge‑Position der Textsignatur, die die Anzeigereihenfolge überlappender Signaturen bestimmt. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Übergeben Sie das Zertifikat und das Erscheinungsbild‑Bild an den Konstruktor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Zeigen Sie die Signatur auf der Seite an dieser Position und Größe
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # In der Signatur gespeicherte Informationen
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Aufgabenleitfäden, die `DigitalSignOptions` verwenden:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
