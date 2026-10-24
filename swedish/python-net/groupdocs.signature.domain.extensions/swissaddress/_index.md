---
title: "SwissAddress-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar adressen för borgenären eller gäldenären."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Representerar adressen för borgenären eller gäldenären.

Du kan antingen ange gata, husnummer, postnummer och ort (strukturerad adresstyp) eller adressrad 1 och 2 (kombinerad adresselementtyp).

SwissAddress-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | Adressrad 1, som innehåller gatunamn, husnummer eller postbox, är valfri och används endast för kombinerade elementadresser. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | Adressrad 2, som innehåller postnummer och ort, är obligatorisk för kombinerade elementadresser. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | Den tvåbokstaviga ISO-landkoden. Landkoden är obligatorisk om inte hela adressen innehåller null- eller tomma värden. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | Husnumret. Detta fält används endast för strukturerade adresser och är valfritt. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | Namnet, antingen för- och efternamn på en fysisk person eller företagsnamnet på en juridisk person. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | Postnumret. Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | Gatan i adressen, utan husnummer; valfri och används endast för strukturerade adresser. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | Ort eller stad, används endast för strukturerade adresser och är obligatorisk för denna typ. |

### Se även
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
