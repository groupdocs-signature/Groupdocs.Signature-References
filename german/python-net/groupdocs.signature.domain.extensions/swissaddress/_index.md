---
title: "SwissAddress-Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Adresse des Gläubigers oder Schuldners dar."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Stellt die Adresse des Gläubigers oder Schuldners dar.

Sie können entweder Straße, Hausnummer, Postleitzahl und Ort (strukturierter Adresstyp) oder Adresszeile 1 und 2 (kombinierter Adress-Elementtyp) festlegen.

Der SwissAddress-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | Die Adresszeile 1, die Straßenname, Hausnummer oder Postfach enthält, ist optional und wird nur für kombinierte Elemente-Adressen verwendet. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | Die Adresszeile 2, die die Postleitzahl und den Ort enthält, ist für kombinierte Elemente-Adressen obligatorisch. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | Der zweibuchstabige ISO-Ländercode. Der Ländercode ist obligatorisch, es sei denn, die gesamte Adresse enthält null oder leere Werte. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | Die Hausnummer. Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | Der Name, entweder Vor- und Nachname einer natürlichen Person oder der Firmenname einer juristischen Person. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | Die Postleitzahl. Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | Die Straße der Adresse, ohne Hausnummer; optional und wird nur für strukturierte Adressen verwendet. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | Der Ort oder die Stadt, wird nur für strukturierte Adressen verwendet und ist für diesen Typ obligatorisch. |

### Siehe auch
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
