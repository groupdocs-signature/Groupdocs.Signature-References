---
title: "SwissAddress-klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt het adres van de crediteur of schuldenaar."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Vertegenwoordigt het adres van de crediteur of schuldenaar.

U kunt ofwel straat, huisnummer, postcode en plaats (gestructureerd adrestype) instellen, of adresregel 1 en 2 (gecombineerd adreselementtype).

Het type SwissAddress bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | Adresregel 1, die de straatnaam, het huisnummer of een postbus bevat, is optioneel en wordt alleen gebruikt voor adressen met gecombineerde elementen. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | Adresregel 2, die de postcode en plaats bevat, is verplicht voor adressen met gecombineerde elementen. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | De tweeletterige ISO-landcode. De landcode is verplicht, tenzij het volledige adres null‑ of lege waarden bevat. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | Het huisnummer. Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | De naam, ofwel de voor‑ en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | De postcode. Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | De straat van het adres, zonder huisnummer; optioneel en alleen gebruikt voor gestructureerde adressen. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | De plaats of stad, alleen gebruikt voor gestructureerde adressen en verplicht voor dit type. |

### Zie ook
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
