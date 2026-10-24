---
title: "DigitalSignature-klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De klasse bevat digitale handtekeningeigenschappen."
type: docs
url: /nl/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

De klasse bevat digitale handtekeningeigenschappen.

Het DigitalSignature-type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | Initialiseert een digitale handtekening met standaardparameters. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | Initialiseert een digitale handtekening met een bekende handtekeningidentificatie. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | Initialiseert een DigitalSignature met het eerste certificaat uit de opgegeven X509-opslag. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | Initialiseert een DigitalSignature op basis van de opgegeven X509-opslag en certificaatindex. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | Initialiseert een digitale handtekening met het opgegeven certificaat. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | Kloont de barcode-handtekeninginstantie. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | Vergelijkt deze handtekening met een andere handtekening op gelijkheid. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | Retourneert de hashcode voor de digitale handtekening. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Laadt digitale handtekeningen uit alle systeem X509-certificaatopslagplaatsen. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Laadt digitale handtekeningen uit een certificaatopslag. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Laadt digitale handtekeningen uit een certificaatopslag. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Laadt digitale handtekeningen uit een digitale certificaatopslag op een specifieke locatie. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Laadt digitale handtekeningen uit een digitale certificaatopslag geplaatst op een specifieke locatie. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Het X509-certificaat dat aan de digitale handtekening is gekoppeld. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | De aangepaste opslagnaam van het certificaat. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | De opslaglocatie van het certificaat. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | De opslagnaam van het certificaat. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | De ondertekeningsdoelopmerking. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | De digitale handtekening is geldig en het document is niet gemanipuleerd. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Het tijdstip waarop het document is ondertekend. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | De vingerafdruk van een certificaat. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Het XAdES-type ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | De datum van handtekeningcreatie. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | De vlag die aangeeft of deze handtekening uit het document is verwijderd. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | De hoogte van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | De vlag die aangeeft of dit component een handtekening (`True`) of documentinhoud (`False`) vertegenwoordigt. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | De linkse positie van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | De wijzigingsdatum van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Het paginanummer waarop de handtekening werd gevonden. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | De unieke identificatie van de handtekening, gebruikt om de handtekening in het document te wijzigen via update- of delete-bewerkingen. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Het type handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | De bovenste positie van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | De breedte van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
