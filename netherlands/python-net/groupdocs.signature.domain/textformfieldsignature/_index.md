---
title: "TextFormFieldSignature klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt tekstinvoerveld handtekeningeigenschappen voor PDF‑documenten voor."
type: docs
url: /nl/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

Stelt tekstinvoerveld handtekeningeigenschappen voor PDF‑documenten voor.

Het TextFormFieldSignature type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | Initialiseert een PdfTextFormFieldSignature met een vooraf gedefinieerde naam. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | Initialiseert een PdfTextFormFieldSignature met een vooraf gedefinieerde naam. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | Kloon FormField Signature instantie. |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | Vergelijkt deze handtekening met een andere handtekening op gelijkheid op basis van type en eigenschapswaarden. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | Overschrijft de GetHashCode-methode. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | De tekst van de invoer van het formulier. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | De datum van handtekeningcreatie. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | De vlag die aangeeft of deze handtekening uit het document is verwijderd. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | De hoogte van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | De vlag die aangeeft of dit component een handtekening (`True`) of documentinhoud (`False`) vertegenwoordigt. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | De linkse positie van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | De wijzigingsdatum van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | De unieke naam van het formulier-veld. (geërfd van [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Het paginanummer waarop de handtekening werd gevonden. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | De unieke identificatie van de handtekening, gebruikt om de handtekening in het document te wijzigen via update- of delete-bewerkingen. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Het type handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | De bovenste positie van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | Het type formulier-veld. (geërfd van [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | Het gegevensobject van het formulier-veld. (geërfd van [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | De breedte van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # Maak een tekstformulierveld met de naam "FieldText" en de waarde "Value1"
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # Maak formulieropties hiervoor aan
        options = FormFieldSignOptions(text_field)

        # Stel de positie en grootte van het formulier in
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # Onderteken het document en sla het resultaat op
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
