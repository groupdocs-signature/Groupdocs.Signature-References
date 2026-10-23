---
title: "Mailmark2D Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Kodiert und dekodiert den im Royal Mail 2D Mailmark eingebetteten Text."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Kodiert und dekodiert den im Royal Mail 2D Mailmark eingebetteten Text.

Der Mailmark2D-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Initialisiert kombinierte Daten von Royal Mail Mailmark mit Standardwerten für primäre und sekundäre Daten. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | Gibt eine Kopie dieses Objekts zurück. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | Die Klasse des Elements. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | Der optionale Raum zur Nutzung durch den Kunden. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | Der Codiermodus des DataMatrix-Barcodes. Standardwert: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | Der 2D‑Mailmark‑Typ definiert die Größe des Data Matrix-Barcodes. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | Die Eigenschaft enthält die Postleitzahl der Lieferadresse mit DPS, die für Binnenadressen aus einem Gebiet (1‑2 Zeichen), einem Bezirk (1‑2 Zeichen), einem Sektor (1 Zeichen), einer Einheit (2 Zeichen) und DPS (2 Zeichen) besteht, einem gültigen PAF®‑Format entsprechen muss und eine maximale Länge von 9 Zeichen hat. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | Der Bezeichner der Royal Mail Mailmark-Barcode‑Nutzlast für jeden Produkttyp. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | Der eindeutige Artikelbezeichner innerhalb der Supply‑Chain‑ID, der auf jedem Mailmark‑Barcode für eine eindeutige Identifizierung von mindestens 90 Tagen erforderlich ist (maximaler Wert: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | Der Rücksende‑Postleitzahl ohne DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | Das Flag, das angibt, welche Ebene des Rücksende‑Dienstes angefordert wird. Maximale Länge ist 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | Die eindeutige Gruppe von Kunden, die am Versand beteiligt ist. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | Die UPU-Länder‑ID (maximale Länge: 4 Zeichen). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | Der Barcode‑Versionsbezeichner, der für jede Informations‑Typ‑ID relevant ist. |

### Siehe auch
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
