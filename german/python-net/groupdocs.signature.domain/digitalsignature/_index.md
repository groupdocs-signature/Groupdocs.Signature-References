---
title: "Klasse DigitalSignature"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die Klasse enthält Eigenschaften digitaler Signaturen."
type: docs
url: /de/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

Die Klasse enthält Eigenschaften digitaler Signaturen.

Der Typ DigitalSignature stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | Initialisiert eine digitale Signatur mit Standardparametern. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | Initialisiert eine digitale Signatur mit einer bekannten Signatur-ID. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | Initialisiert ein DigitalSignature unter Verwendung des ersten Zertifikats aus dem angegebenen X509-Store. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | Initialisiert ein DigitalSignature basierend auf dem angegebenen X509-Store und dem Zertifikatsindex. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | Initialisiert eine digitale Signatur mit dem angegebenen Zertifikat. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | Klonen der Barcode-Signaturinstanz. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | Vergleicht diese Signatur mit einer anderen Signatur auf Gleichheit. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | Gibt den Hashcode für die digitale Signatur zurück. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Lädt digitale Signaturen aus allen System-X509-Zertifikatsstores. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Lädt digitale Signaturen aus einem Zertifikatspeicher. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Lädt digitale Signaturen aus einem Zertifikatspeicher. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Lädt digitale Signaturen aus einem digitalen Zertifikatspeicher, der an einem bestimmten Ort abgelegt ist. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Lädt digitale Signaturen aus einem digitalen Zertifikatspeicher, der an einem bestimmten Ort abgelegt ist. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Das X509-Zertifikat, das mit der digitalen Signatur verknüpft ist. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Der benutzerdefinierte Store-Name des Zertifikats. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Der Speicherort des Zertifikats. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Der Store-Name des Zertifikats. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Der Kommentar zum Signaturzweck. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Die digitale Signatur ist gültig und das Dokument wurde nicht manipuliert. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Der Zeitpunkt, zu dem das Dokument signiert wurde. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Der Fingerabdruck eines Zertifikats. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Der XAdES-Typ ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Das Erstellungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Die Höhe der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Das Flag, das angibt, ob diese Komponente eine Signatur (`True`) oder Dokumentinhalt (`False`) darstellt. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Die linke Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Das Änderungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Die Seitenzahl, auf der die Signatur gefunden wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Der eindeutige Bezeichner der Signatur, der verwendet wird, um die Signatur im Dokument über Update- oder Löschvorgänge zu ändern. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Der Typ der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Die obere Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Die Breite der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
